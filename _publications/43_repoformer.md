---
title: "RepoFormer: Selective Retrieval for Repository-Level Code Completion"
collection: 'under_review'
Authors: 'Di Wu, <b>Wasi Uddin Ahmad</b>, Dejiao Zhang, Murali Krishna Ramanathan, and Xiaofei Ma.'
date: 02/2024
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/'
codeurl: 'https://github.com/amazon_science'
excerpt: ''
webpage: 'https://repoformer.github.io'
---
---
<a href='https://arxiv.org/pdf/2212.10233.pdf' target="_blank">[Download Paper]</a><a href='https://github.com/uclanlp/DeepKPG' target="_blank">[Source Code]</a>

<p align="justify">
Recent advances in retrieval-augmented generation (RAG) have initiated a new era in repository-level code completion. However, the invariable use of retrieval in existing methods exposes issues in 
  both efficiency and robustness, with a large proportion of the retrieved contexts proving unhelpful or harmful to code language models (code LMs). To tackle the challenges, this paper proposes a 
  selective RAG framework where retrieval is avoided when unnecessary. To power this framework, we design a self-supervised learning approach that enables a code LM to accurately self-evaluate whether 
  retrieval can improve its output quality and robustly leverage the potentially noisy retrieved contexts. Using this LM as both the selective retrieval policy and the generation model, our framework 
  consistently outperforms the state-of-the-art prompting with an invariable retrieval approach on diverse benchmarks including RepoEval, CrossCodeEval, and a new benchmark. Meanwhile, our selective 
  retrieval strategy results in strong efficiency improvements by as much as 70\% inference speedup without harming the performance. We demonstrate that our framework effectively accommodates different 
  generation models, retrievers, and programming languages. These advancements position our framework as an important step towards more accurate and efficient repository-level code completion.
</p>