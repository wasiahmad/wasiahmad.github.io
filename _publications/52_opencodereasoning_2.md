---
title: "OpenCodeReasoning-II: A Simple Test Time Scaling Approach via Self-Critique"
collection: publications
Authors: '<b>Wasi Uddin Ahmad</b>, Somshubra Majumdar, Aleksander Ficek, Sean Narenthiran, Mehrzad Samadi, Jocelyn Huang, Siddhartha Jain, Vahid Noroozi, and Boris Ginsburg.'
date: 07/2025
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2507.09075'
dataurl: 'https://huggingface.co/datasets/nvidia/OpenCodeReasoning-2'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2507.09075' target="_blank">[Download Paper]</a><a href='https://huggingface.co/datasets/nvidia/OpenCodeReasoning-2' target="_blank">[Download Dataset]</a>
<p align="justify">
Recent advancements in reasoning-based Large Language Models (LLMs), particularly their potential through test-time scaling, have created significant opportunities for distillation in code generation and critique. However, 
  progress in both areas fundamentally depends on large-scale, high-quality datasets. In this work, we introduce OpenCodeReasoning-II, a dataset consists of 2.5M question-solution-critique triples (approx. 35K unique 
  programming questions), making it nearly twice the size of the previous largest publicly available code reasoning dataset. In this work, we employ a two-stage supervised fine-tuning strategy. The first stage focuses on 
  fine-tuning for code generation, while the second stage involves the joint training of models for both code generation and critique. Our resulting finetuned Qwen2.5-Instruct models achieve performance in code generation 
  that either exceeds or equals the best prior open-weight distilled models. Notably, the integration of our code generation and critique models leads to significant improvements in competitive coding performance. 
  Furthermore, we present an extension of the LiveCodeBench benchmark to specifically support the C++ programming language, thereby facilitating more comprehensive LLM evaluation using this benchmark.
</p>
