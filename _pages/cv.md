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
* **B.E. in Electronic Information Engineering**, Harbin Institute of Technology (C9), 2023.09 – 2027.06 (expected)
  * Yongtan Honors Class, Future Technology College / Honors School (directed by Academician Liu Yongtan, recipient of China's Highest Science and Technology Award)
  * GPA: 94.563/100, Rank: 3/76 (top 3.9%)
  * English: CET-4 563, CET-6 548
  * Selected courses: Mathematical Analysis (98), Algebra and Geometry (98), Computer Organization (97), Analog and Digital Circuits (97.5)

Research Experience
======
* **Cross-lingual degradation of in-image text editing in multimodal models** (Aug 2025 – Mar 2026)
  * Built a multilingual in-image text editing benchmark covering 12 languages and 3,600 samples
  * Designed the same-background multilingual data construction method and VLM-based semantic evaluation metrics
  * Revealed and verified significant degradation of in-image text editing in low-resource languages
  * Outcome: first-author paper under review at EMNLP

* **Optical–ISAR multimodal large model for space situational awareness** (Apr 2026 – May 2026)
  * Built a multimodal framework fusing optical images, ISAR images, attitude, and trajectory information
  * Implemented the LLM + SAM pipeline for satellite body and solar-panel extraction
  * Designed and completed multimodal SFT for maneuver-type recognition with interpretable rationale generation
  * Outcome: first-author EI conference paper under review (CIE)

* **Cross-platform universal autonomous navigation with VLN models** (Mar 2026 – present)
  * Training a VLN foundation model on the StarVLA framework: one model adapting to UAVs, UGVs, and mobile robots, SOTA on multiple benchmarks
  * Lead the evaluation module: standardized, automated, reusable pipeline covering 10+ navigation benchmarks (R2R, etc.)

* **Dynamic spatial reasoning VLMs via world-model distillation** (Dec 2025 – Apr 2026)
  * World model as training-time teacher generating post-action viewpoint-shift data
  * Forward/inverse bidirectional SFT distillation combined with task-aware GRPO
  * ~15-point average improvement across four spatial reasoning benchmarks (SAT-Real, etc.)
  * Responsible for viewpoint-shift data generation and bidirectional-supervision QA design

Honors & Awards
======
* National Scholarship, 2025
* National Encouragement Scholarship, 2024
* Merit Student of Heilongjiang Province, 2025
* Outstanding Student of Harbin Institute of Technology, 2024
* Outstanding League Member of Harbin Institute of Technology, 2025
* People's Scholarship (top 3% of the college), four consecutive semesters
* Grand Prize (1st place nationwide), "Challenge Cup" Jiebang-Guashuai Special Track
* First Prize (National), China Undergraduate Mathematical Contest in Modeling (CUMCM)
* Honorable Mention, Mathematical Contest in Modeling (MCM/ICM)
* First Prize (Provincial), China Collegiate Computing Contest
* Second Prize, National Mathematics Competition for College Students (non-math majors)
* Second Prize (Regional), Embedded Chip and System Design Competition

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* Programming: C, Python
* Tools: MATLAB, Git, Visio, Origin
* AI agent development workflows

Service
======
* Volunteer, the 17th CIE International Conference on Radar
* Docent, HIT Space Museum
* 300+ hours of volunteer service in total
