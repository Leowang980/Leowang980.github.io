---
layout: archive
title: "Research Experience"
permalink: /research/
author_profile: true
---

{% include base_path %}


{% for post in site.research reversed %}
    {% include archive-single.html %}
{% endfor %}
### Research Experience

- **Multimedia Lab, Nanyang Technological University (MMLab-NTU)**<br>
  *Oct 2024 - Mar 2026 | Singapore*<br>
  Working closely with **Jingkang Yang** (Ph.D.) in Ziwei Liu's team.
  - **EgoLife**: Supported the construction and annotation of the EgoLife dataset and helped develop **EgoRAG**, a retrieval-augmented generation system for long-form egocentric video understanding.
  - **Ego-R1**: Participated in developing a reasoning-agent framework and benchmark for long egocentric video understanding, focusing on tool-augmented reasoning and evaluation design.
  - **Visual Generation**: Surveyed benchmarks for visual generation tasks, summarizing recent advances, representative methods, evaluation protocols, and emerging research directions.

- **Intelligent and Distributed Computing Lab, HUST & GenMI Research Lab, MBZUAI**<br>
  *Mar 2024 - Present | Wuhan, China*<br>
  Working closely with **Yichen Li** (Ph.D. student).
  - **Heterogeneous Federated Learning**: Developed a feature-distillation framework to address model heterogeneity in federated learning.
  - **Federated Continual Learning**: Led research on frameworks that leverage lightweight features for decoupled replay and statistical prototypes for regularization, mitigating catastrophic forgetting in distributed settings.

### Working Experience

- **Synvo.ai & MMLab-NTU**<br>
  *Research Engineer Intern | Aug 2025 - Mar 2026 | Singapore*
  - Led development of a VLM-powered AI copilot for retail scenarios, covering model training, agent construction, deployment, encryption, and system optimization.
  - Contributed to long-horizon memory construction for smart-glass egocentric streaming videos.
  - Researched feature inversion attacks against VLMs in egocentric scenarios.

- **Action Intelligence**<br>
  *Research Engineer Intern | May 2026 - Present | Shanghai, China*
  - Designing and implementing scalable egocentric data collection pipelines for embodied AI using smart glasses, IMU sensors, AprilTag calibration, hand-pose estimation, and customized hardware.
