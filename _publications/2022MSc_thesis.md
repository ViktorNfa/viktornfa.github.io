---
title: "Control barrier function-enabled human-in-the-loop control for multi-robot systems: Centralized and distributed approaches"
collection: publications
type: "other" # "journal", "conference", "other"
authors: "<b>Nan Fernandez-Ayala V.</b>"
date: 2022-10-31
venue: 'KTH MSc thesis: Degree Project in Electrical Engineering, specializing in Systems, Control and Robotics'
# citation: 'Your Name. &quot;Paper Title.&quot; <i>Journal 1</i>.' # If not defined, the recommended citation is automatically generated
paperurl: 'https://www.diva-portal.org/smash/get/diva2:1707581/FULLTEXT01.pdf' #.pdf file link, can be "http://..." or a file name inside files/
# permalink: /publication/paper-title-number-1
extra_links: # Can have a url with "https://..." or "#section-name" for a reference to a section in this .md page, e.g #media
  - text: Open version
    url: "https://www.diva-portal.org/smash/record.jsf?dswid=2914&pid=diva2%3A1707581"
  - text: Pictures
    url: "#media"
  - text: Bibtex
    url: "#bibtex"
---
{% include base_path %}
## Abstract

Autonomous multi-robot systems have found many real-world applications
in factory settings, rescue tasks and light shows. Albeit these successful
applications, the multi-robot system is usually pre-programmed with limited
flexibility for online adaptation. Having a human-in-the-loop feature would
provide additional flexibility such as handling unexpected situations, detecting
and correcting bad behaviours and supporting the automated decision making.
In addition, it would also allow for an extra level of cooperation between the
robots and the human that facilitates certain real-world tasks, for example in
the agricultural sector.
Control barrier functions (CBFs), as a convenient modular-design tool,
will be mainly explored. CBFs have seen a lot of development in recent years
and extending them to the field of multi-robot systems is still new. In particular,
creating an original distributed approach, instead of a centralized one, will be
one of the key topics of this Master’s thesis project.
In this thesis work, several multi-robot coordination protocols and safety
constraints will be identified and these constraints will be enforced using a
control barrier function-enabled mixer module. This module will take in
the commands from both the planner and the human operator, prioritizing
the commands from the human operator as long as the safety constraints
are not violated. Otherwise, the mixer module will filter the commands and
send out a safe alternative. The underlying multi-robot tasks are expected to
be achieved whenever feasible. Simulations in ROS, Python and MATLAB
environments are developed to experimentally assess the safety and optimality
of the system, and experiments with real robots in a lab are performed to show
the applicability of this algorithm.
Finally, a distributed approach to the mixer module has been developed,
based on previous research and extended to allow for more versatility. This
is of key importance since it would allow each robot to compute its own
controller based on local information, making the multi-robot system both
more robust and flexible to be deployed on real-world applications.
{: .text-justify}

## Media
Picture of the experimental setup with robots and artificial vineyard.

![me herding the robots with the CBF controller]({{base_path}}/images/icra23/robots.jpg){: width="1000" }

## BibTex

```bibtex
@misc{2022MSc_thesis,
  author       = {Fernandez-Ayala, V. Nan},
  title        = {Control Barrier Function-Enabled Human-in-the-Loop Control for Multi-Robot Systems: Centralized and Distributed Approaches},
  howpublished = {\url{https://www.diva-portal.org/smash/get/diva2:1707581/FULLTEXT01.pdf}},
  year         = {2022},
  note         = {Dissertation}
}
```