---
permalink: /
title: "Welcome!"
classes: wide
layout: single
author_profile: true
redirect_from: 
  - /home/
  - /home.html
---


I’m Yitong Li, a Master's student in the **College of Computing** at **Georgia Tech**, where I am advised by Professor [Bo Dai](https://bo-dai.github.io/). I earned my Bachelor's degree in Computer Science with a minor in Mathematics, also from **Georgia Tech**.

My research interests focus on efficient **representation learning**, with an emphasis on domains such as reinforcement learning, self-supervised learning, and generative models. I have conducted research on various aspects of enhancing efficiency in representation learning: memory efficiency \([AmorLip](#amorlip)\), sample efficiency \([DiffRep](#diffrep)\), data efficiency \([ProgGen](#proggen)\).

## In Preparation
- **AmorLip: Amortizations for Language-Image Pretraining**
  <br/>
  _**Yitong Li**\*, Haotian Sun\*, Yucheng Zhuang, Hanjun Dai, Bo Dai_
  <br/>
  <a id="amorlip"></a>
  <!-- [[Paper](https://arxiv.org/abs/2406.16121)]
  [[Code](https://github.com/haotiansun14/rl-rep/tree/main/agent/diffsrdrq)]\\ -->
  We designed a novel method with amortized objectives and exponential moving average to reduce memory dependency on negative samples and large batch size, reducing memory consumption from 130GB to 80GB, achieving performance comparable to CLIP.

## Publications

- (NeurIPS 2024) **Diffusion Spectral Representation for Reinforcement Learning**
  <br/>
  _Dmitry Shribak\*, Chen-Xiao Gao\*, **Yitong Li**, Chenjun Xiao, Bo Dai_
  <br/>
  <a id="diffrep"></a>
  [[Paper](https://arxiv.org/abs/2406.16121)]
  [[Code](https://github.com/haotiansun14/rl-rep/tree/main/agent/diffsrdrq)]\\
  We propose an algorithm that leverages the flexibility of diffusion models for representation learning to enable efficient policy optimization, mitigating the time-consuming sampling process typically involved in diffusion models.


- (ACL 2024 Findings) **ProgGen: Generating Named Entity Recognition Datasets Step-by-step with Self-Reflexive Large Language Models**
  <br/>
  _Yuzhao Heng, Chunyuan Deng, **Yitong Li**, Yue Yu, Yinghao Li, Rongzhi Zhang, Chao Zhang_
  <br/>
  <a id="proggen"></a>
  [[Paper](https://arxiv.org/abs/2210.10464)]
  [[Code](https://github.com/StefanHeng/ProgGen)]\\
  We propose a LLMs-based framework to generate diverse and accurate task-specific datasets from very few-shot samples via requirement sampling and self-reflection.


## Education
**Georgia Institute of Technology**  
- M.S. in Computer Science, Specialization in Machine Learning (2023 – Present)  
- B.S. in Computer Science, Minor in Mathematics (2019 – 2023)

## Service
Reviewer for ICLR 2024