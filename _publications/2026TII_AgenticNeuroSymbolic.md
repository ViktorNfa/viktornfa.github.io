---
title: "Agentic Neuro–Symbolic Planning and Commissioning for Human-in-the-Loop Industrial Robotics with Digital Twins"
collection: publications
type: "journal" # "journal", "conference", "other"
authors: "Liu Z., <b>Nan Fernandez-Ayala V.</b>, Wang T., Qin Q., Vincent Wang X., V. Dimarogonas D. and Wang L."
date: 2026-06-06
venue: 'IEEE Transactions on Industrial Informatics (TII)'
# citation: 'Your Name. &quot;Paper Title.&quot; <i>Journal 1</i>.' # If not defined, the recommended citation is automatically generated
paperurl: 'https://arxiv.org/pdf/2606.08214' #.pdf file link, can be "http://..." or a file name inside files/
# permalink: /publication/paper-title-number-1
extra_links: # Can have a url with "https://..." or "#section-name" for a reference to a section in this .md page, e.g #media
  - text: Open version
    url: "https://arxiv.org/abs/2606.08214"
  - text: Pictures
    url: "#media"
  - text: Bibtex
    url: "#bibtex"
---
{% include base_path %}
## Abstract

Flexible robotic automation requires systems that interpret operator intent, verify physical feasibility, and recover from execution failures across both the planning and execution stages. This paper proposes an agentic neuro-symbolic framework for human-in-the-loop industrial robotics, in which LLMs are used for tasks that require language understanding or contextual reasoning, while all verification, sequencing, and execution remain deterministic. The framework adapts the Planner-GeneratorEvaluator (PGE) harness pattern from software engineering into a Specifier-Designer-Inspector (SDI) architecture for industrial robotics, combined with LangGraph-based dynamic routing for failure recovery. A two-tier recovery mechanism addresses structure-level replanning through context-aware orchestration and execution-level geometric failures through deterministic recovery skills. A Unity3D digital twin supports human inspection, modification, and re-verification prior to physical execution. Evaluated on natural-language commands across multiple difficulty levels against ten baselines, the proposed method achieves the highest task success. Ablation results confirm that structured command expansion, symbolic verification, selective LLM routing, and recovery skills are each individually necessary.
{: .text-justify}

## Media
Picture of the sequence that th neuro-symbolic algorithm follows.

![robot architecture]({{base_path}}/images/tii26/algo_sequence.png){: width="1000" }

## BibTex

```bibtex
@misc{liu2026agenticneurosymbolicplanningcommissioning,
      title={Agentic Neuro-Symbolic Planning and Commissioning for Human-in-the-Loop Industrial Robotics with Digital Twins}, 
      author={Zhihao Liu and Victor Nan Fernandez-Ayala and Tianyu Wang and Qiang Qin and Xi Vincent Wang and Dimos V. Dimarogonas and Lihui Wang},
      year={2026},
      eprint={2606.08214},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2606.08214}, 
}
```