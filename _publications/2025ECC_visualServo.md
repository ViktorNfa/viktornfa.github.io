---
title: "Robust Visual Servoing under Human Supervision for Assembly Tasks"
collection: publications
type: "conference" # "journal", "conference", "other"
authors: "<b>Nan Fernandez-Ayala V.</b>, Silva J., Guo M. and V. Dimarogonas D."
date: 2025-06-24
venue: 'European Control Conference (ECC)'
# citation: 'Your Name. &quot;Paper Title.&quot; <i>Journal 1</i>.' # If not defined, the recommended citation is automatically generated
paperurl: 'https://arxiv.org/pdf/2504.12506' #.pdf file link, can be "http://..." or a file name inside files/
# permalink: /publication/paper-title-number-1
extra_links: # Can have a url with "https://..." or "#section-name" for a reference to a section in this .md page, e.g #media
  - text: Open version
    url: "https://arxiv.org/abs/2504.12506"
  - text: Pictures
    url: "#media"
  - text: Bibtex
    url: "#bibtex"
---
{% include base_path %}
## Abstract

We propose a framework enabling mobile manipulators to reliably complete pick-and-place tasks for assembling structures from construction blocks. The picking uses an eye-in-hand visual servoing controller for object tracking with Control Barrier Functions (CBFs) to ensure fiducial markers in the blocks remain visible. An additional robot with an eye-to-hand setup ensures precise placement, critical for structural stability. We integrate human-in-the-loop capabilities for flexibility and fault correction and analyze robustness to camera pose errors, proposing adapted barrier functions to handle them. Lastly, experiments validate the framework on 6-DoF mobile arms.
{: .text-justify}

## Media
Picture of the algorithmic setup for picking and placing.

![picking setup]({{base_path}}/images/ecc25/picking.png){: width="1000" }
![placing setup]({{base_path}}/images/ecc25/placing.png){: width="1000" }

## BibTex

```bibtex
@misc{ECC25_visualServo,
      title={Robust Visual Servoing under Human Supervision for Assembly Tasks}, 
      author={Victor Nan Fernandez-Ayala and Jorge Silva and Meng Guo and Dimos V. Dimarogonas},
      year={2025},
      eprint={2504.12506},
      archivePrefix={arXiv},
      primaryClass={eess.SY},
      url={https://arxiv.org/abs/2504.12506},
}
```