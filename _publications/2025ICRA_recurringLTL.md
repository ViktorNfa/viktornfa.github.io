---
title: "Efficient Coordination and Synchronization of Multi-Robot Systems Under Recurring Linear Temporal Logic"
collection: publications
type: "conference" # "journal", "conference", "other"
authors: "Peron D., <b>Nan Fernandez-Ayala V.</b>, Vlahakis E. E. and V. Dimarogonas D."
date: 2025-05-19
venue: 'International Conference on Robotics and Automation (ICRA)'
# citation: 'Your Name. &quot;Paper Title.&quot; <i>Journal 1</i>.' # If not defined, the recommended citation is automatically generated
paperurl: 'https://ieeexplore.ieee.org/document/11127554' #.pdf file link, can be "http://..." or a file name inside files/
# permalink: /publication/paper-title-number-1
extra_links: # Can have a url with "https://..." or "#section-name" for a reference to a section in this .md page, e.g #media
  - text: Open version
    url: "https://arxiv.org/abs/2502.16531"
  - text: Pictures
    url: "#media"
  - text: Bibtex
    url: "#bibtex"
---
{% include base_path %}
## Abstract

We consider multi-robot systems under recurring tasks formalized as linear temporal logic (LTL) specifications. To solve the planning problem efficiently, we propose a bottom-up approach combining offline plan synthesis with online coordination, dynamically adjusting plans via real-time communication. To address action delays, we introduce a synchronization mechanism ensuring coordinated task execution, leading to a multi-agent coordination and synchronization framework that is adaptable to a wide range of multi-robot applications. The software package is developed in Python and ROS2 for broad deployment. We validate our findings through lab experiments involving nine robots showing enhanced adaptability compared to previous methods. Additionally, we conduct simulations with up to ninety agents to demonstrate the reduced computational complexity and the scalability features of our work.
{: .text-justify}

## Media
Picture of the experimental setup with nine robots in an artificial vineyard.

![experiment setup]({{base_path}}/images/icra25/recurringLTL.png){: width="1000" }

## BibTex

```bibtex
@misc{ICRA25_recurringLTL,
      title={Efficient Coordination and Synchronization of Multi-Robot Systems Under Recurring Linear Temporal Logic}, 
      author={Davide Peron and Victor Nan Fernandez-Ayala and Eleftherios E. Vlahakis and Dimos V. Dimarogonas},
      year={2025},
      eprint={2502.16531},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2502.16531}, 
}
```