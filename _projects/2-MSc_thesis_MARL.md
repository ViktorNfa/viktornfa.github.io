---
title: "Scalable MARL for collision avoidance"
excerpt: "Scalable multi-agent reinforcement learning for formation control with collision avoidance. This work was my Master's Thesis while at KTH Royal Institute of Technology."
collection: projects
# paperurl: "https://link_to_related_paper"
# link: "https://to_official_page_of_the_project"
cover_gallery:
  - image_path: "https://user-images.githubusercontent.com/46297629/216676961-4b61d1f0-9b1e-4ca9-ad81-2c36c6a77886.gif"
    alt: "5 agents moving"
    title: "5 agents moving towards formation"
  - image_path: "msc_thesis/n10_good.gif"
    alt: "10 agents moving"
    title: "10 agents moving towards formation"
gallery_agents:
  - image_path: "msc_thesis/n10_good.gif"
    alt: "10 agents moving"
    title: "10 agents moving towards formation"
  - image_path: "https://user-images.githubusercontent.com/46297629/216676961-4b61d1f0-9b1e-4ca9-ad81-2c36c6a77886.gif"
    alt: "5 agents moving"
    title: "5 agents moving towards formation"
---

The code generated to implement the scalable MARL algorithm can be found in this [repository](https://github.com/AndreuMatoses/scalable-collision-avoidance-RL).

{% include gallery id="gallery_agents" caption="Five agents with limited sensing range moving towards formation while avoiding collisions" %}

This work is part of my Mater's Thesis at the Royal Institute of Technology (KTH), Stockholm, Sweden (URL available soon). The scalable part of this work is inspired by the paper [Scalable Reinforcement Learning for Multi-Agent Networked Systems](https://arxiv.org/abs/1912.02906). The approach presented on the thesis exploits the structure of the designed reward to present \\(\Delta\\)-disk local approximation of the individual Q functions and policy gradients.

## Important Scripts

- [drone_env.py](https://github.com/AndreuMatoses/scalable-collision-avoidance-RL/blob/main/drone_env.py): Script containing the environment class and its methods. The main methods follow the structure of the OpenGym RL environments, such as `.step()` and `.reset()`.
- [train_problem.py](https://github.com/AndreuMatoses/scalable-collision-avoidance-RL/blob/main/train_problem.py): Script containing the training of the main problem.
- [SAC_agents.py](https://github.com/AndreuMatoses/scalable-collision-avoidance-RL/blob/main/SAC_agents.py): Script containing the agent classes and its policy classes
- [benchmark_agent.py](https://github.com/AndreuMatoses/scalable-collision-avoidance-RL/blob/main/benchmark_agent.py): Scripts to run trained agents and benchmark their performance

## Training of the scalable agents

The schema of the algorithm used is presented below. The scalable actor-critic agents are trained for each robotic agent. There are a total of *n* agents.

![image](https://user-images.githubusercontent.com/46297629/216669445-a07214a4-08e5-46d8-85e5-f30855f3e8fc.png){: width="600" }{: .align-center}

## Structure of the training script

![image](https://user-images.githubusercontent.com/46297629/216669814-5e9465ef-f0a8-46cb-a53a-35645a799e70.png){: width="600" }{: .align-center}

## Relevant results

### Softmax discrete policy

The individual policy for each agent is of the shape:

![image](https://user-images.githubusercontent.com/46297629/216673328-1cea1dc8-26fe-4b50-9618-ccf30043801e.png)

Some examples of trajectories obtained after successful training are as follow

![image](https://user-images.githubusercontent.com/46297629/216674048-68c2473c-b398-4d60-8bfc-de6049065911.png)

### Continous normally distributed policy

The individual policy for each agent is of the shape:

![image](https://user-images.githubusercontent.com/46297629/216673469-c5b07220-ee01-4d7f-a1bf-010b21619b19.png)

Some examples of trajectories obtained after successful training are as follow

![image](https://user-images.githubusercontent.com/46297629/216673912-91e69f5a-f6dc-49b3-ac77-fed1a8cecec5.png)

## Comparison of tested policies

The number of collisions displayed on the results are defined as an agent intersection with a neighbour’s collision radius in a given time step. Each agent counts collisions separately, thus two agents colliding is counted as two different collisions and a collisions that lasts for several times steps is is also counted as different collisions.

Percentage of simulations that achieve each number of collisions for each of the three tested policies, n = 5. The percentages for more than 14 collisions (under 1%) have been omitted.

![image](https://user-images.githubusercontent.com/46297629/216673529-5bf6a5be-c149-43cd-b0d7-ead7099d29dd.png)

Effect of the ∆-disk radius (definition 12 on the thesis) on the global reward and number of collisions, averaged over 2000 runs of the trained policies, for the discrete softmax NN policy

![image](https://user-images.githubusercontent.com/46297629/216673581-b48750c7-eedc-4e04-92d4-21ade45c398a.png)

The results also show that the average reward starts to decrease after a certain value of \\( \Delta_i \\) , in this case around 1. The average number of collisions also increases sharply back to values where the agent has nearly no vision. This unexpected behaviours is the result of significant increase in the complexity of the maximization problem that the policy gradient is trying to solve. Taking into account an increasing number of neighbours and from further distances, increases the variance of the estimated approximated gradient and as a result, the policy used is not able to find improvements. Indeed, for the final case of \\( \Delta_i \approx \hat{d}_{i} \\) is not able to converge during training.
