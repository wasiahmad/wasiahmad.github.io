---
title: "CrossCodeEval: A Diverse and Multilingual Benchmark for Cross-File Code Completion"
collection: publications
Authors: 'Yangruibo Ding<sup>*</sup>, Zijian Wang<sup>*</sup>, <b>Wasi Uddin Ahmad</b><sup>*</sup>, Hantian Ding, Ming Tan, Nihal Jain, Murali Krishna Ramanathan, Ramesh Nallapati, Parminder Bhatia, Dan Roth, and Bing Xiang.'
date: 09/2023
venue: 'NeurIPS Datasets and Benchmarks Track'
paperurl: 'https://arxiv.org/abs/2310.11248'
codeurl: ''
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2310.11248.pdf' target="_blank">[Download Paper]</a><a href='' target="_blank">[Source Code]</a>

<p align="justify">
Code completion models have made significant progress in recent years, yet current popular evaluation datasets, such as HumanEval, MBPP, and PY150, only focus on code completion tasks within a single file. 
  This over-simplified setting falls short of representing the real-world software development scenario where repositories are built across multiple files with many cross-file dependencies, where cross-file 
  context is often required to complete the code correctly. 
To fill in this gap, we propose CrossCodeEval, a diverse and multilingual code completion benchmark that necessitates cross-file contextual understanding to complete the code accurately. 
  CrossCodeEval is built on a diverse set of real-world, open-sourced, permissively licensed repositories in four popular programming languages: Python, Java, TypeScript, and C#. 
  To create examples that strictly require cross-file context to be completed correctly, we propose a simple yet efficient static-analysis-based approach to locate the cross-file context usages in the 
  current file. Extensive experiments on state-of-the-art code language models like CodeGen and StarCoder demonstrate that CrossCodeEval is challenging when the right cross-file context is not presented to 
  the model, and we see significant improvements in performance when the cross-file context is included in the prompt. We hope CrossCodeEval can facilitate research and development of code completion with 
  cross-file context that better reflects how a code completion model performs in real-world software development scenarios.
</p>
