---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
classes: wide
redirect_from:
  - /about/
  - /about.html
---

I am a final-year Ph.D. candidate at the <a href="https://mli.kaist.ac.kr/">Machine Learning and Intelligence Lab</a> at KAIST, advised by <a href="https://scholar.google.com/citations?user=UWO1mloAAAAJ">Prof. Eunho Yang</a>.

### Research Focus
My research centers on efficient inference for large-scale foundation models, with a broader interest in efficient training and post-training. I primarily approach efficiency from an algorithmic perspective, but I am especially interested in methods that remain effective under real hardware and system constraints. In other words, I care not only about improving algorithmic metrics, but also about whether those improvements translate into meaningful reductions in latency, memory usage, and computational cost in realistic workloads. This perspective has naturally led me to study the interaction between algorithms and the characteristics of modern accelerators, memory hierarchies, parallel execution, and serving systems.

### Current Research Directions
My recent work focuses on several complementary directions toward practical acceleration of large-scale models. One major direction is efficient reinforcement learning for language models, particularly accelerating RLVR rollouts through techniques such as quantized inference and efficient scheduling. I am also continuing to work on speculative decoding, with an emphasis on making it genuinely effective in realistic serving settings such as large-batch, high-throughput, and offline inference, rather than optimizing acceptance-related metrics in isolation. Quantization is another central theme in my research, both as a standalone compression technique and as a building block that can be integrated with other acceleration methods. More broadly, I am interested in understanding how efficiency bottlenecks change across workloads and architectures, and in designing methods that are tailored to those changing bottlenecks rather than assuming a single inference regime.

### Broader Vision
Looking forward, I am particularly interested in efficiency challenges arising from new workloads, model architectures, and modalities. This includes agentic and long-horizon inference, multimodal models, sparse and linear attention, mixture-of-experts models, and other architectures whose computational behavior differs substantially from conventional dense autoregressive models. I believe these shifts will create new opportunities for algorithmic acceleration, but will also require a more careful understanding of workload structure, hardware utilization, memory behavior, and system-level constraints. My broader goal is to develop principled and practically effective algorithms that make increasingly capable models faster, more resource-efficient, and more economical to train and deploy. While my current focus is on inference, my earlier work in optimization and memory-efficient learning also provides a broader foundation for studying efficiency across the full lifecycle of modern foundation models.

## Publications & Research Works (Last Updated: Oct. 2026)

- **KV4-RL: Unlocking Faster Asynchronous Rollouts for RLVR with INT4 KV Cache Quantization** \\
**Sihwan Park**, Sung-Yub Kim, Doohyuk Jang, Eunho Yang \\
*Preprint (2026)*

- <a href="https://arxiv.org/abs/2501.19099">
**Learning Beyond What You Sample: Off-Policy-Aware Cross-Model Trajectory Exchange for RLVR**
</a> \\
Doohyuk Jang, Yoonsik Park, Gyouk Chu, **Sihwan Park**, Eunho Yang \\
*Preprint (2026)*

- <a href="https://aclanthology.org/2026.acl-long.172/">
**Bringing Real-World Relations into Video Generation with Graph-Structured Knowledge** \\
Joonhyung Park<sup>†</sup>, Jaeyun Song<sup>†</sup>, **Sihwan Park**, Eunho Yang
(<sup>†</sup>: Equal Contribution) \\
*ACL 2026*

- <a href="https://arxiv.org/abs/2501.19099">
**Elucidating Subspace Perturbation in Zeroth-Order Optimization: Theory and Practice at Scale**
</a> \\
**Sihwan Park<sup>†</sup>**, Jihun Yun<sup>†</sup>, Sung-Yub Kim, Souvik Kundu, Eunho Yang
(<sup>†</sup>: Equal Contribution) \\
*Preprint (2025)*

- <a href="https://arxiv.org/abs/2502.06352">
**LANTERN++: Enhancing Relaxed Speculative Decoding with Static Tree Drafting for Visual Auto-regressive Models**
</a> \\
**Sihwan Park<sup>†</sup>**, Doohyuk Jang<sup>†</sup>, Sung-Yub Kim, Souvik Kundu, Eunho Yang
(<sup>†</sup>: Equal Contribution) \\
*ICLR 2025 Workshop on Scalable Optimization for Efficient and Adaptive Foundation Models (Best Paper Runner-up)*

- <a href="https://arxiv.org/abs/2410.03355">
**LANTERN: Accelerating Visual Autoregressive Models with Relaxed Speculative Decoding**
</a> \\
Doohyuk Jang<sup>†</sup>, **Sihwan Park<sup>†</sup>**, June Yong Yang, Yeonsung Jung, Jihun Yun, Souvik Kundu, Sung-Yub Kim, Eunho Yang
(<sup>†</sup>: Equal Contribution) \\
*ICLR 2025*

- <a href="https://openreview.net/pdf?id=OBIuFjZzmp">
**MeZO-A<sup>3</sup>dam: Memory-efficient Zeroth-order Adam with Adaptivity Adjustments for Fine-tuning LLMs**
</a> \\
**Sihwan Park<sup>†</sup>**, Jihun Yun<sup>†</sup>, Sung-Yub Kim, June Yong Yang, Yeonsung Jung, Souvik Kundu, Kyungsu Kim, Eunho Yang 
(<sup>†</sup>: Equal Contribution) \\
*Preprint (2024)*

- <a href="https://openreview.net/pdf?id=VZ5EaTI6dqa">
**Scale-invariant Bayesian Neural Networks with Connectivity Tangent Kernel**
</a> \\
Sung-Yub Kim, **Sihwan Park**, Kyungsu Kim, Eunho Yang \\
*ICLR 2023 (Spotlighted)*

- <a href="../assets/papers/master_thesis.pdf">
**On the Understanding of Sharpness-aware Minimization and its Application: A Perspective on Escape Efficiency and Asymmetric Valley**
</a> \\
**Sihwan Park**
*Master's Thesis, KAIST*

- <a href="https://openreview.net/pdf?id=Mvf5zr2qs6">
**Bias Decay Matters: Improving Large Batch Optimization with Connectivity Sharpness** 
</a> \\
Sung-Yub Kim, **Sihwan Park**, Yong-Deok Kim, Eunho Yang \\
*Preprint (2021)*

<!---
- <a href="../assets/papers/paper1.pdf">
**Scalable Task Segmentation Method Based on Change Point Detection of Multi-sensors in Smart Spaces**
</a> \\
**Sihwan Park**, Hyunju Kim, Dongman Lee \\
*Proceedings of the Korean Information Science Society Conference 2018, pp.1764-1766, Jun 2018, (Honorable Mention Award)*
-->

## Education

- **Ph.D.** in Graduate School of AI, <a href="https://gsai.kaist.ac.kr/">**Korea Advanced Institute of Science and Technology (KAIST)**</a>\\
*Sep. 2022 - Present*
  - Advised by [Prof. Eunho Yang](https://scholar.google.com/citations?user=UWO1mloAAAAJ)
  
- **M.S.** in Graduate School of AI, <a href="https://gsai.kaist.ac.kr/">**Korea Advanced Institute of Science and Technology (KAIST)**</a>\\
*Sep. 2020 - Aug. 2022*
  - Advised by [Prof. Eunho Yang](https://scholar.google.com/citations?user=UWO1mloAAAAJ)

- **B.S.** in Computer Science and Mathematical Sciences, **Korea Advanced Institute of Science and Technology (KAIST)**\\
*Mar. 2015 - Aug. 2020*


## Research Experience
- Research Intern, **Computer Architecture and Systems Lab, KAIST**, Daejeon, <font size="3">Aug. 2019 - Dec. 2019</font>
  - Advisor : [Prof. Jaehyuk Huh](https://jaehyuk-huh.github.io/)
  - Low-level security techniques of Intel SGX and secure container with KVSSD

- Research Intern, **Collaborative Distributed Systems and Networking Lab, KAIST**, Daejeon, <font size="3">Jan. 2018 - Oct. 2018</font>
  - Advisor : [Prof. Dongman Lee](http://143.248.55.123/cdsn/?p=29)
  - Signal data processing for IoT task recognition and framework for task segmentation

## Selected Research Projects & Collaborations

- Efficient Foundation Models on Intel Systems \\
**Intel Corporation & NAVER**, *Sep.2024-Aug.2025*

- A Study on Conversational Large Language Models for Virtual Physicians in Patient Intake \\
**AITRICS**, *Apr.2024-May.2024*

- A Study on Optimization and Network Interpretation Method for Large-Scale Machine Learning \\
**National Research Foundation of Korea (NRF) grant funded by the Korea government (MSIT)**, *Mar.2023-Feb.2027*
  
- A Study on Statistically and Computationally Efficient Parameter Structures for Machine Learning Algorithms \\
**National Research Foundation of Korea (NRF) grant funded by the Korea government (MSIT)**, *Mar.2021-Dec.2022*
