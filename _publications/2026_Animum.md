---
title: "From Pixels to Shelf: End-to-End Algorithmic Control of a Mobile Manipulator for Supermarket Stocking and Fronting"
collection: publications
type: "other" # "journal", "conference", "other"
authors: "Peron D., <b>Nan Fernandez-Ayala V.</b> and Segelmark L."
date: 2025-09-16
venue: 'Animum - Fronta startup - Technical report'
# citation: 'Your Name. &quot;Paper Title.&quot; <i>Journal 1</i>.' # If not defined, the recommended citation is automatically generated
paperurl: 'https://arxiv.org/pdf/2509.11740' #.pdf file link, can be "http://..." or a file name inside files/
# permalink: /publication/paper-title-number-1
extra_links: # Can have a url with "https://..." or "#section-name" for a reference to a section in this .md page, e.g #media
  - text: Open version
    url: "https://arxiv.org/abs/2509.11740"
  - text: Pictures
    url: "#media"
  - text: Bibtex
    url: "#bibtex"
---
{% include base_path %}
## Abstract

Autonomous stocking in retail environments, particularly supermarkets, presents challenges due to dynamic human interactions, constrained spaces, and diverse product geometries. This paper introduces an efficient end-to-end robotic system for autonomous shelf stocking and fronting, integrating commercially available hardware with a scalable algorithmic architecture. A major contribution of this work is the system integration of off-the-shelf hardware and ROS2-based perception, planning, and control into a single deployable platform for retail environments. Our solution leverages Behavior Trees (BTs) for task planning, fine-tuned vision models for object detection, and a two-step Model Predictive Control (MPC) framework for precise shelf navigation using ArUco markers. Laboratory experiments replicating realistic supermarket conditions demonstrate reliable performance, achieving over 98% success in pick-and-place operations across a total of more than 700 stocking events. However, our comparative benchmarks indicate that the performance and cost-effectiveness of current autonomous systems remain inferior to that of human workers, which we use to highlight key improvement areas and quantify the progress still required before widespread commercial deployment can realistically be achieved.
{: .text-justify}

## Media
Picture of the integrated solution on a mock-up store.

![robots predictions]({{base_path}}/images/animum/robotic_stocking.png){: width="1000" }

## BibTex

```bibtex
@misc{fernandezayala2025estimatingunknowndynamicscost,
      title={From Pixels to Shelf: End-to-End Algorithmic Control of a Mobile Manipulator for Supermarket Stocking and Fronting}, 
      author={Davide Peron and Victor Nan Fernandez-Ayala and Lukas Segelmark},
      year={2025},
      eprint={2509.11740},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2509.11740}, 
}
```