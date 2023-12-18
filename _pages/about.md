---
permalink: /
# title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
  - /home/
---
{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}
![wide image of me](images/wide_glacier_crevice.jpg)

# About me

I am a first-year PhD candidate for Learning and Autonomous Control (LAC) at the Department of Cognitive Robotics (CoR), Delft University of Technology. I am supervised by Professor [Javier Alonso-Mora](https://www.autonomousrobots.nl/) and Professor [Robert Babuska](http://www.robertbabuska.com/). My research focuses on task and motion planning in multiagent systems accounting for interaction and cooperation between other agents and humans.
<!-- {: .text-justify} -->

Before coming to Delft, I obtained my bachelor's degree in aerospace engineering from Universitat Politècnica de València (Spain), and a master's degree from KTH Royal institute of Technology (Sweden). After my MSc, I worked as a research engineer at KTH for Professor [Dimos Dimarogonas’s](https://people.kth.se/~dimos/) group.
<!-- {: .text-justify} -->

## News

- **July 2023.** I will be in Prague (CTU) for the IEEE RAS Summer School on Multi-Robot Systems.
- **June 2023.** I am starting my PhD at TU Delft at the cognitive robotics department.
- **September 2022.** I am working as a research engineer at the Smart Mobility Lab for Prof. Dimos Dimarogonas' group in KTH.
