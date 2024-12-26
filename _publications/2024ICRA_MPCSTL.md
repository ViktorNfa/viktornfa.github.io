---
title: "Multi-robot Human-in-the-loop Control under Spatiotemporal Specifications"
collection: publications
type: "conference" # "journal", "conference", "other"
authors: "Zhang Y., <b>Nan Fernandez-Ayala V.</b> and V. Dimarogonas D."
date: 2024-05-13
venue: 'International Conference on Robotics and Automation (ICRA)'
# citation: 'Your Name. &quot;Paper Title.&quot; <i>Journal 1</i>.' # If not defined, the recommended citation is automatically generated
paperurl: 'https://ieeexplore.ieee.org/document/10610123' #.pdf file link, can be "http://..." or a file name inside files/
# permalink: /publication/paper-title-number-1
extra_links: # Can have a url with "https://..." or "#section-name" for a reference to a section in this .md page, e.g #media
  - text: Open version
    url: "https://www.diva-portal.org/smash/get/diva2:1899217/FULLTEXT01.pdf"
  - text: Pictures
    url: "#media"
  - text: Bibtex
    url: "#bibtex"
---
{% include base_path %}
## Abstract

In this work, we present a coordination strategy tailored for scenarios involving multiple agents and tasks. We devise a range of tasks using signal temporal logic (STL), each earmarked for specific agents. These tasks are then imposed through control barrier function (CBF) constraints to ensure completion. To extend existing methodologies, our framework adeptly manages interactions among multiple agents. This extension is facilitated by leveraging nonlinear model predictive control (NMPC) to compute trajectories that avoid collisions. An integral aspect of our approach is the integration of a human-in-the-loop (HIL) model. This model enables real-time integration of human directives into the coordination process. A novel task allocation protocol is embedded within the frame-work to guide this process. We substantiate our methodology through a series of experiments, which corroborate the viability and relevance of our algorithms.
{: .text-justify}

## Media
Picture of the experimental setup with robots and artificial vineyard.

![experiment setup]({{base_path}}/images/icra24/experiment_setup.png){: width="1000" }

## BibTex

```bibtex
@inproceedings{ICRA24_MPC_STL,
  author={Zhang, Yixiao and Fernandez-Ayala, Victor Nan and Dimarogonas, Dimos V.},
  booktitle={2024 IEEE International Conference on Robotics and Automation (ICRA)}, 
  title={Multi-robot Human-in-the-loop Control under Spatiotemporal Specifications}, 
  year={2024},
  volume={},
  number={},
  pages={4841-4847},
  keywords={Protocols;Computational modeling;Robot kinematics;Human in the loop;Real-time systems;Trajectory;Spatiotemporal phenomena},
  doi={10.1109/ICRA57147.2024.10610123}
}
```