---
title: "ConstrucTwin: Digital Twin-Driven Multirobot Construction System Toward Industry 5.0"
collection: publications
type: "journal" # "journal", "conference", "other"
authors: "Liu Z., Silva J., Zhong R., Qin Q., Roy N., <b>Nan Fernandez-Ayala V.</b>, Lesko J., Håkansson U., Sandberg S., V. Dimarogonas D., Gross J., Vincent Wang X. and Wang L."
date: 2026-02-19
venue: 'IEEE Transactions on Systems, Man, and Cybernetics: Systems'
# citation: 'Your Name. &quot;Paper Title.&quot; <i>Journal 1</i>.' # If not defined, the recommended citation is automatically generated
paperurl: 'https://ieeexplore.ieee.org/document/11399914' #.pdf file link, can be "http://..." or a file name inside files/
# permalink: /publication/paper-title-number-1
extra_links: # Can have a url with "https://..." or "#section-name" for a reference to a section in this .md page, e.g #media
  - text: Open version
    url: "https://ieeexplore.ieee.org/document/11399914"
  - text: Pictures
    url: "#media"
  - text: Bibtex
    url: "#bibtex"
---
{% include base_path %}
## Abstract

Rapid advancements in digitalization and artificial intelligence (AI) have catalyzed the adoption of digital twin technologies in the construction sector, enabling real-time synchronization between virtual models and physical systems. Simultaneously, on-site robotic automation has shown promise for reducing physical workloads, enhancing productivity, and contributing to sustainability goals that are key values of Industry 5.0. However, current digital twin implementations rarely incorporate multirobot construction systems, often relying on single-robot approaches or purely offline simulations. This gap hinders the realization of truly integrated construction environments that combine sensing, data analytics, wireless communications, and multirobot coordination. In response, this article proposes ConstrucTwin, a digital twin-driven multirobot construction framework designed to support complex construction tasks in real-world settings. By combining a 5G communication estimation-involved architecture and a cross-level planning strategy, ConstrucTwin streamlines interactions between physical robots and their digital counterparts. Essential tasks such as motion and task-level planning, as well as remote human-in-the-loop (HIL) oversight, are orchestrated within a single unified architecture. Through case studies involving rebar cage and brick wall construction, we demonstrate how an integrated approach to vision-based servoing and multirobot coordination enhances execution speed, precision, and scalability. The results underscore the system’s potential to advance human-centric, resilient, and sustainable construction, thereby aligning with the broader vision of Industry 5.0.
{: .text-justify}

## Media
Picture of the digital-twin robotic architecture used for the work.

![robot architecture]({{base_path}}/images/tsmc26/fig4.jpg){: width="1000" }

## BibTex

```bibtex
@ARTICLE{11399914,
  author={Liu, Zhihao and Silva, Jorge and Zhong, Ruirui and Qin, Qiang and Roy, Neelabhro and Nan Fernandez-Ayala, Victor and Lesko, Johan and Håkansson, Ulf and Sandberg, Sara and Dimarogonas, Dimos V. and Gross, James and Vincent Wang, Xi and Wang, Lihui},
  journal={IEEE Transactions on Systems, Man, and Cybernetics: Systems}, 
  title={ConstrucTwin: Digital Twin-Driven Multirobot Construction System Toward Industry 5.0}, 
  year={2026},
  volume={},
  number={},
  pages={1-16},
  keywords={Robots;Digital twins;Service robots;Multi-robot systems;Robot kinematics;Planning;Fifth Industrial Revolution;5G mobile communication;Safety;Artificial intelligence;Digital twin;Industry 5.0;multirobot construction;smart construction},
  doi={10.1109/TSMC.2026.3658622}}
```