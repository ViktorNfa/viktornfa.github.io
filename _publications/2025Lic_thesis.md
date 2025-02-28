---
title: "Distributed planning and control of multi-robot systems under human presence"
collection: publications
type: "other" # "journal", "conference", "other"
authors: "<b>Nan Fernandez-Ayala V.</b>"
date: 2025-03-11
venue: 'KTH Licentiate thesis, monograph'
# citation: 'Your Name. &quot;Paper Title.&quot; <i>Journal 1</i>.' # If not defined, the recommended citation is automatically generated
paperurl: 'https://www.diva-portal.org/smash/get/diva2:1937629/FULLTEXT01.pdf' #.pdf file link, can be "http://..." or a file name inside files/
# permalink: /publication/paper-title-number-1
extra_links: # Can have a url with "https://..." or "#section-name" for a reference to a section in this .md page, e.g #media
  - text: Open version
    url: "https://www.diva-portal.org/smash/record.jsf?dswid=2914&pid=diva2%3A1937629"
  - text: Pictures
    url: "#media"
  - text: Bibtex
    url: "#bibtex"
---
{% include base_path %}
## Abstract

The increasing integration of robotics into dynamic, safety-critical environments has necessitated the development of frameworks that enable seamless collaboration between humans and multi-robot systems. This thesis investigates the distributed planning and control of multi-robot systems under human presence, focusing on explicit and implicit Human-(multi)Robot Interaction (HRI) across both low-level control and high-level planning tasks. In this context, explicit means interaction through direct commands and implicit means interaction through indirect effects due to shared spaces. The contributions of this work aim to bridge human intuition and robotic precision, ensuring safety and task efficiency while addressing real-world challenges in domains such as precision agriculture and smart construction.

The first part of the thesis addresses explicit low-level human-in-the-loop (HIL) control by developing distributed barrier-function-based approaches that incorporate multiple safety constraints in multi-robot systems. This framework allows human input or overrides while ensuring inter-agent collision avoidance, connectivity maintenance, and adherence to spatial limits. A novel method transforms multiple safety constraints into a collective constraint using a smoothly approximated minimum function, enabling efficient optimization. Experiments demonstrate the integration of HIL scenarios in collaborative multi-robot tasks, highlighting robustness in maintaining system safety despite human interventions. Additionally, a robust Control Barrier Function (CBF)-based visual servoing framework for mobile manipulators is introduced, combining eye-in-hand and eye-to-hand setups. This approach ensures precise object tracking and placement under human supervision, crucial for safety-critical applications such as robotic assembly and construction.

The second part focuses on explicit high-level HIL planning, where Signal Temporal Logic (STL) and Linear Temporal Logic (LTL) are used to define spatiotemporal tasks for multi-robot systems. These tasks are executed using Model Predictive Control (MPC), enabling real-time, collision-free trajectory planning while dynamically incorporating human commands. A task allocation protocol ensures adaptability and safe integration of human directives in scenarios involving complex tasks, such as collaborative harvesting and pruning in precision agriculture. Laboratory and field experiments conducted in vineyards validate the applicability of this framework in dynamic environments. Further contributions include the development of methods for recurring task coordination and synchronization in large-scale multi-robot teams. These methods leverage recurring LTL formulations to address computational challenges associated with scaling, enabling robust synchronization and adaptability in real-world settings with up to ninety robots.

The final part of the thesis explores implicit low-level HIL by focusing on human motion prediction to enable safe and intuitive interactions between humans and robots. A Koopman-based Inverse Optimal Control (IOC) framework is introduced to estimate unknown dynamics and costs for human motion prediction. By reformulating human-related dynamics as bilinear systems, this method provides a robust and tractable alternative to traditional nonlinear IOC approaches. This framework is validated through theoretical analysis, simulation studies, and experiments, demonstrating its efficacy in enhancing human-aware navigation and task execution in multi-robot systems.

The overarching vision of this thesis is to develop scalable, human-centric frameworks that enable robots to dynamically adapt to human inputs while ensuring safety and operational efficiency. By addressing explicit and implicit HRI across low-level control and high-level planning, the work presented here lays the foundation for the seamless integration of multi-robot systems into dynamic, real-world environments, advancing the state of the art in human-robot collaboration.
{: .text-justify}

## Media
Picture of the robot used and recorded trajectories for prediction.

![me herding the robots with the CBF controller]({{base_path}}/images/icra23/robots.jpg){: width="1000" }

## BibTex

```bibtex
@misc{2025Lic_thesis,
  author       = {Fernandez-Ayala, V. Nan},
  title        = {Distributed Planning and Control of Multi-Robot Systems Under Human Presence},
  howpublished = {\url{https://www.diva-portal.org/smash/get/diva2:1937629/FULLTEXT01.pdf}},
  year         = {2025},
  note         = {Licentiate Dissertation, KTH Royal Institute of Technology}
}
```