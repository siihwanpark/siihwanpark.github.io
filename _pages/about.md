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

I'm a Ph.D candidate at [Machine Learning and Intelligence Lab](https://mli.kaist.ac.kr/) (MLILab) in KAIST, advised by [Prof. Eunho Yang](https://scholar.google.com/citations?user=UWO1mloAAAAJ).

### Research Interests
My primary research interest lies in improving the computational and memory efficiency of training and inference in foundation models, with a particular focus on large language models (LLMs). Recently, I proposed a relaxed speculative decoding method designed to accelerate autoregressive generation in multimodal models. Currently, I am investigating the potential of speculative decoding to accelerate LLM inference in large-batch settings, challenging the prevailing assumption that large-batch inference is inherently compute-bound and cannot benefit from speculative approaches. Moving forward, I plan to expand my research beyond speculative decoding, exploring various techniques such as parallel decoding, KV cache compression, quantization, and their algorithmic integration to enhance efficiency further. On the optimization front, my recent work includes zeroth-order optimization methods for memory-efficient fine-tuning of large-scale models. I also intend to develop efficient algorithms for accelerating reinforcement learning pipelines and effective fine-tuning methods explicitly tailored for quantized LLMs. 

### Background and Insights
In the earlier stages of my research, I focused on theoretical aspects of generalization and optimization dynamics in deep neural networks. Specifically, I conducted sharpness-based analyses of loss landscapes, provided theoretical insights into generalization, and proposed improved sharpness-aware minimization algorithms. These foundational insights continue to inform my current research, offering a principled foundation for designing effective and efficient methods for both training and inference in modern foundation models.

## Publications (Last Updated: Jul 2025)

- <a href="https://arxiv.org/abs/2501.19099">
**Elucidating Subspace Perturbation in Zeroth-Order Optimization: Theory and Practice at Scale**
</a> \\
**Sihwan Park<sup>†</sup>**, Jihun Yun<sup>†</sup>, Sung-Yub Kim, Souvik Kundu, Eunho Yang
(<sup>†</sup>: Equal Contribution) \\
*Preprint (2025)*


- **Bringing Real-World Relations into Video Generation with Graph-Structured Knowledge** \\
Joonhyung Park<sup>†</sup>, Jaeyun Song<sup>†</sup>, **Sihwan Park**, Eunho Yang
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
**MeZO-A^3dam: Memory-efficient Zeroth-order Adam with Adaptivity Adjustments for Fine-tuning LLMs**
</a> \\
**Sihwan Park<sup>†</sup>**, Jihun Yun<sup>†</sup>, Sung-Yub Kim, June Yong Yang, Yeonsung Jung, Souvik Kundu, Kyungsu Kim, Eunho Yang 
(<sup>†</sup>: Equal Contribution) \\
*Preprint (2024)*

- <a href="https://openreview.net/pdf?id=VZ5EaTI6dqa">
**Scale-invariant Bayesian Neural Networks with Connectivity Tangent Kernel**
</a> \\
Sung-Yub Kim, **Sihwan Park**, Kyungsu Kim, Eunho Yang \\
*ICLR 2023 (Spotlighted)*

- <a href="https://openreview.net/pdf?id=Mvf5zr2qs6">
**Bias Decay Matters: Improving Large Batch Optimization with Connectivity Sharpness** 
</a> \\
Sung-Yub Kim, **Sihwan Park**, Yong-Deok Kim, Eunho Yang (2022)

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
  
- **M.S.** in Graduate School of AI, <a href="https://gsai.kaist.ac.kr/">**Korea Advanced Institute of Science and Technology (KAIST)**</a>\\
*Sep. 2020 - Aug. 2022*
  - Advised by [Prof. Eunho Yang](https://scholar.google.com/citations?user=UWO1mloAAAAJ)
  - Master's Thesis: <a href="../assets/papers/master_thesis.pdf">**On the Understanding of Sharpness-aware Minimization and its Application: A Perspective on Escape Efficiency and Asymmetric Valley**</a>

- **B.S.** in Computer Science, <a href="https://cs.kaist.ac.kr">**Korea Advanced Institute of Science and Technology (KAIST)**</a>\\
*Mar. 2015 - Aug. 2020*

- **B.S.** in Mathematical Science, <a href="https://mathsci.kaist.ac.kr">**Korea Advanced Institute of Science and Technology (KAIST)**</a>\\
*Mar. 2015 - Aug. 2020*

## Experiences
- Research Intern, **Computer Architecture and Systems Lab, KAIST**, Daejeon, <font size="3">Aug. 2019 - Dec. 2019</font>
  - Advisor : [Prof. Jaehyuk Huh](https://jaehyuk-huh.github.io/)
  - Low-level security techniques of Intel SGX and secure container with KVSSD

- Research Intern, **Collaborative Distributed Systems and Networking Lab, KAIST**, Daejeon, <font size="3">Jan. 2018 - Oct. 2018</font>
  - Advisor : [Prof. Dongman Lee](http://143.248.55.123/cdsn/?p=29)
  - Signal data processing for IoT task recognition and framework for task segmentation

- Exchange Student, **University of California, Santa Cruz**, Santa Cruz, CA, <font size="3">Jun. 2019 - Aug. 2019</font>
  - Software engineering and computer game basics

## Projects

- Sub-task generation based point/regional Out-Of-Distribution detection \\
**Samsung Electronics**, *Mar.2021-Sep.2025*

- Predicting graph properties with few labels using Graph Neural Networks \\
**Samsung Electronics**, *Mar.2021-Sep.2025*

- A Study on Statistically and Computationally Efficient Parameter Structures for Machine Learning Algorithms \\
**National Research Foundation of Korea (NRF) grant funded by the Korea government (MSIT)**, *Mar.2021-Dec.2022*
  
- A Study on Optimization and Network Interpretation Method for Large-Scale Machine Learning \\
**National Research Foundation of Korea (NRF) grant funded by the Korea government (MSIT)**, *Mar.2023-Feb.2027*

- A Study on Conversational Large Language Models for Virtual Physicians in Patient Intake \\
**AITRICS**, *Apr.2024-May.2024*

- Efficient Foundation Models on Intel Systems \\
**Intel Corporation & NAVER**, *Sep.2024-Aug.2025*

