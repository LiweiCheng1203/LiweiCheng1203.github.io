---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **B.E. in Electronic Information Engineering**, Harbin Institute of Technology, 2023.09 – 2027.06 (expected)
  * Yongtan Honors Class, Future Technology College / Honors School

Research Experience
======
* **Cross-lingual degradation of in-image text editing in multimodal models** (Aug 2025 – Mar 2026)
  * Built a multilingual in-image text editing benchmark covering 12 languages and 3,600 samples, with VLM-based semantic evaluation metrics
  * Revealed significant degradation of in-image text editing in low-resource languages
  * First-author paper under review at EMNLP

* **Optical–ISAR multimodal large model for space situational awareness** (Apr 2026 – May 2026)
  * Built a multimodal framework fusing optical images, ISAR images, attitude, and trajectory information for interpretable space target recognition
  * First-author EI conference paper under review (CIE)

* **Cross-platform universal autonomous navigation with VLN models** (Mar 2026 – present)
  * Training a VLN foundation model on the StarVLA framework: one model adapting to UAVs, UGVs, and mobile robots
  * Lead the standardized, automated evaluation pipeline covering 10+ navigation benchmarks (R2R, etc.)

* **Dynamic spatial reasoning VLMs via world-model distillation** (Dec 2025 – Apr 2026)
  * World model as training-time teacher generating post-action viewpoint-shift data; bidirectional SFT distillation with task-aware GRPO
  * ~15-point average improvement across four spatial reasoning benchmarks (SAT-Real, etc.)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
