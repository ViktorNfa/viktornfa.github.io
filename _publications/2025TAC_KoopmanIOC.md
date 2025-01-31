---
title: "Estimating unknown dynamics and cost as a bilinear system with Koopman-based Inverse Optimal Control"
collection: publications
type: "journal" # "journal", "conference", "other"
authors: "<b>Nan Fernandez-Ayala V.</b>, Deka S. A. and V. Dimarogonas D."
date: 2025-01-30
venue: 'IEEE Transactions on Automatic Control (submitted)'
# citation: 'Your Name. &quot;Paper Title.&quot; <i>Journal 1</i>.' # If not defined, the recommended citation is automatically generated
paperurl: 'https://arxiv.org/pdf/2501.18318' #.pdf file link, can be "http://..." or a file name inside files/
# permalink: /publication/paper-title-number-1
extra_links: # Can have a url with "https://..." or "#section-name" for a reference to a section in this .md page, e.g #media
  - text: Open version
    url: "https://arxiv.org/abs/2501.18318"
  - text: Pictures
    url: "#media"
  - text: Bibtex
    url: "#bibtex"
---
{% include base_path %}
## Abstract

In this work, we address the challenge of approximating unknown system dynamics and costs by representing them as a bilinear system using Koopman-based Inverse Optimal Control (IOC). Using optimal trajectories, we construct a bilinear control system in transformed state variables through a modified Extended Dynamic Mode Decomposition with control (EDMDc) that maintains exact dynamical equivalence with the original nonlinear system. We derive Pontryagin's Maximum Principle (PMP) optimality conditions for this system, which closely resemble those of the inverse Linear Quadratic Regulator (LQR) problem due to the consistent control input and state independence from the control. This similarity allows us to apply modified inverse LQR theory, offering a more tractable and robust alternative to nonlinear Inverse Optimal Control methods, especially when dealing with unknown dynamics. Our approach also benefits from the extensive analytical properties of bilinear control systems, providing a solid foundation for further analysis and application. We demonstrate the effectiveness of the proposed method through theoretical analysis, simulation studies and a robotic experiment, highlighting its potential for broader applications in the approximation and design of control systems.
{: .text-justify}

## Media
Picture of the robot used and recorded trajectories for prediction.

![me herding the robots with the CBF controller]({{base_path}}/images/tac25/robots_prediction.png){: width="1000" }

## BibTex

```bibtex
@misc{fernandezayala2025estimatingunknowndynamicscost,
      title={Estimating unknown dynamics and cost as a bilinear system with Koopman-based Inverse Optimal Control}, 
      author={Victor Nan Fernandez-Ayala and Shankar A. Deka and Dimos V. Dimarogonas},
      year={2025},
      eprint={2501.18318},
      archivePrefix={arXiv},
      primaryClass={eess.SY},
      url={https://arxiv.org/abs/2501.18318}, 
}
```