---
title: "Distributed barrier function-enabled human-in-the-loop control for multi-robot systems"
collection: publications
type: "conference" # "journal", "conference", "other"
authors: "<b>Nan Fernandez-Ayala V.</b>, Tan X. and V. Dimarogonas D."
date: 2023-06-04
venue: 'International Conference on Robotics and Automation (ICRA)'
# citation: 'Your Name. &quot;Paper Title.&quot; <i>Journal 1</i>.' # If not defined, the recommended citation is automatically generated
paperurl: 'https://ieeexplore.ieee.org/document/10160974' #.pdf file link, can be "http://..." or a file name inside files/
# permalink: /publication/paper-title-number-1
extra_links: # Can have a url with "https://..." or "#section-name" for a reference to a section in this .md page, e.g #media
  - text: Open version
    url: "https://people.kth.se/~dimos/pdfs/ICRA23_HIL_MAS.pdf"
  - text: Pictures
    url: "#media"
  - text: Bibtex
    url: "#bibtex"
---
{% include base_path %}
## Abstract

In this work, we propose a distributed control
scheme for multi-robot systems in the presence of multiple
constraints using control barrier functions. The proposed
scheme expands previous work where only one single constraint
can be handled. Here we show how to transform multiple
constraints to a collective one using a smoothly approximated
minimum function. Additionally, human-in-the-loop control is
also incorporated seamlessly to our control design, both through
the nominal control in the optimization objective as well as a
safety condition in the constraints. Possible failure regions are
identified and a suitable fix is proposed. Two types of human-in-the-
loop scenarios are tested on real multi-robot systems with
multiple constraints, including collision avoidance, connectivity
maintenance, and arena range limits.
{: .text-justify}

## Media
Picture of the experimental setup with robots and artificial vineyard.

![me herding the robots with the CBF controller]({{base_path}}/images/icra23/robots.jpg){: width="1000" }

## BibTex

```bibtex
@inproceedings{ICRA23_HIL_MAS,
  author={Fernandez-Ayala, Victor Nan and Tan, Xiao and Dimarogonas, Dimos V.},
  booktitle={2023 IEEE International Conference on Robotics and Automation (ICRA)}, 
  title={Distributed barrier function-enabled human-in-the-loop control for multi-robot systems}, 
  year={2023},
  volume={},
  number={},
  pages={7706-7712},
  doi={10.1109/ICRA48891.2023.10160974}
}
```