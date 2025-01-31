---
title: "Enhancing Precision Agriculture Through Human-in-the-Loop Planning and Control"
collection: publications
type: "conference" # "journal", "conference", "other"
authors: "Shankar A. D., Sujet P., Matoses Gimenez A., <b>Nan Fernandez-Ayala V.</b>, Wong R., Yu P., Tan X. and V. Dimarogonas D."
date: 2024-08-28
venue: 'Conference on Automation Science and Engineering (CASE)'
# citation: 'Your Name. &quot;Paper Title.&quot; <i>Journal 1</i>.' # If not defined, the recommended citation is automatically generated
paperurl: 'https://ieeexplore.ieee.org/document/10711319' #.pdf file link, can be "http://..." or a file name inside files/
# permalink: /publication/paper-title-number-1
extra_links: # Can have a url with "https://..." or "#section-name" for a reference to a section in this .md page, e.g #media
  - text: Open version
    url: "https://www.diva-portal.org/smash/get/diva2:1912874/FULLTEXT01.pdf"
  - text: Pictures
    url: "#media"
  - text: Bibtex
    url: "#bibtex"
---
{% include base_path %}
## Abstract

In this paper, we introduce a ROS based framework designed for the planning and control of robotic systems within the context of precision agriculture, with an emphasis on human-in-the-loop capabilities. Utilizing Linear Temporal Logic to articulate complex task specifications, our algorithm creates high-level robotic plans that are not only correct by design but also adaptable in real time by human operators. This dual-focus approach ensures that while humans have the flexibility to modify the high-level plan on-the-fly or even take over low-level control of the robots, the system inherently safeguards against any human actions that could potentially breach the predefined task specifications. We demonstrate our algorithm within the dynamic and challenging environment of a real vineyard, where the collaboration between human workers and robots is critical for tasks such as harvesting and pruning, and show the practical applicability and robustness of our software. This work marks a pioneering application of formal methods to complex, real-world agricultural environments.
{: .text-justify}

## Media
Picture of the experimental setup at the field.

![experiment setup field]({{base_path}}/images/case24/Canopies_hardware_3-min.png){: width="1000" }

## BibTex

```bibtex
@inproceedings{CASE24_LTL_MAS,
  author={Deka, Shankar A. and Phodapol, Sujet and Gimenez, Andreu Matoses and Fernandez-Ayala, Victor Nan and Wong, Rufus and Yu, Pian and Tan, Xiao and Dimarogonas, Dimos V.},
  booktitle={2024 IEEE 20th International Conference on Automation Science and Engineering (CASE)}, 
  title={Enhancing Precision Agriculture Through Human-in-the-Loop Planning and Control}, 
  year={2024},
  volume={},
  number={},
  pages={78-83},
  keywords={Precision agriculture;Heuristic algorithms;Software algorithms;Robustness;Human in the loop;Software;Real-time systems;Planning;Robots;Multi-agent systems},
  doi={10.1109/CASE59546.2024.10711319}
}
```