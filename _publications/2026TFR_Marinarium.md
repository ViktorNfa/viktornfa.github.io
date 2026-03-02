---
title: "Marinarium: a New Arena to Bring Maritime Robotics Closer to Shore"
collection: publications
type: "journal" # "journal", "conference", "other"
authors: "Torroba I., Dorner D., <b>Nan Fernandez-Ayala V.</b>, Kartasev M., Verhagen J., Krantz E., Marchesini G., Ljung C., Roque P., Sidrane C., Van der Spaa L., De Carli N., Ogren P., Fuglesang C., Tumova J., V. Dimarogonas D. and Stenius I."
date: 2026-03-02
venue: 'IEEE Transactions on Field Robotics'
# citation: 'Your Name. &quot;Paper Title.&quot; <i>Journal 1</i>.' # If not defined, the recommended citation is automatically generated
paperurl: 'https://arxiv.org/pdf/2602.23053' #.pdf file link, can be "http://..." or a file name inside files/
# permalink: /publication/paper-title-number-1
extra_links: # Can have a url with "https://..." or "#section-name" for a reference to a section in this .md page, e.g #media
  - text: Open version
    url: "https://arxiv.org/abs/2602.23053"
  - text: Pictures
    url: "#media"
  - text: Bibtex
    url: "#bibtex"
---
{% include base_path %}
## Abstract

This paper presents the Marinarium, a modular and stand-alone underwater research facility designed to provide a realistic testbed for maritime and space-analog robotic experimentation in a resource-efficient manner. The Marinarium combines a fully instrumented underwater and aerial operational volume, extendable via a retractable roof for real-weather conditions, a digital twin in the SMaRCSim simulator and tight integration with a space robotics laboratory. All of these result from design choices aimed at bridging simulation, laboratory validation, and field conditions. We compare the Marinarium to similar existing infrastructures and illustrate how its design enables a set of experiments in four open research areas within field robotics. First, we exploit high-fidelity dynamics data from the tank to demonstrate the potential of learning-based system identification approaches applied to underwater vehicles. We further highlight the versatility of the multi-domain operating volume via a rendezvous mission with a heterogeneous fleet of robots across underwater, surface, and air. We then illustrate how the presented digital twin can be utilized to reduce the reality gap in underwater simulation. Finally, we demonstrate the potential of underwater surrogates for spacecraft navigation validation by executing spatiotemporally identical inspection tasks on a planar space-robot emulator and a neutrally buoyant \gls{rov}. In this work, by sharing the insights obtained and rationale behind the design and construction of the Marinarium, we hope to provide the field robotics research community with a blueprint for bridging the gap between controlled and real offshore and space robotics experimentation.
{: .text-justify}

## Media
Picture of the Marinarium underwater testing facility.

![Marinarium]({{base_path}}/images/tsmc26/tank_top.jpg){: width="1000" }

## BibTex

```bibtex
@misc{torroba2026marinariumnewarenabring,
      title={Marinarium: a New Arena to Bring Maritime Robotics Closer to Shore}, 
      author={Ignacio Torroba and David Dorner and Victor Nan Fernandez-Ayala and Mart Kartasev and Joris Verhagen and Elias Krantz and Gregorio Marchesini and Carl Ljung and Pedro Roque and Chelsea Sidrane and Linda Van der Spaa and Nicola De Carli and Petter Ogren and Christer Fuglesang and Jana Tumova and Dimos V. Dimarogonas and Ivan Stenius},
      year={2026},
      eprint={2602.23053},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2602.23053}, 
}
```