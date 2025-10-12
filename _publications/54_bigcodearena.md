---
title: "BigCodeArena: Unveiling More Reliable Human Preferences in Code Generation via Execution"
collection: publications
Authors: 'Terry Yue Zhuo, Xiaolong Jin, Hange Liu, Juyong Jiang, Tianyang Liu, Chen GONG, Bhupesh Bishnoi, Vaisakhi Mishra, Marek Suppa, Noah Ziems, Saiteja Utpala, Ming Xu, Guangyu Song, Kaixin Li, Yuhan Cao, Bo Liu, Zheng Liu, Sabina Abdurakhmanova, Wenhao Yu, Mengzhao Jia, Jihan Yao, Kenneth Hamilton, Kumar Shridhar, Vu Minh Chien, Dingmin Wang, Jiawei Liu, Zijian Wang, Qian Liu, Binyuan Hui, Meg Risdal, Ahsen Khaliq, Atin Sood, Zhenchang Xing, <b>Wasi Uddin Ahmad</b>, John C. Grundy, David Lo, Banghua Zhu, Xiaoning Du, Torsten Scholak, Leandro Von Werra.'
date: 10/2025
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/?'
codeurl: 'https://github.com/bigcode-project/bigcodearena'
dataurl: 'https://huggingface.co/collections/bigcode/bigcodearena-68cd3a196e5147cc45f8ea3d'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/?' target="_blank">[Download Paper]</a><a href='https://huggingface.co/collections/bigcode/bigcodearena-68cd3a196e5147cc45f8ea3d' target="_blank">[Download Dataset]</a>
<p align="justify">
Crowdsourced model evaluation platforms, such as Chatbot Arena, enable real-time evaluation from human perspectives to assess the quality of model 
  responses. In the coding domain, manually examining the quality of LLM-generated content is extremely challenging, as it requires understanding 
  long chunks of raw code and deliberatively simulating code execution. To this end, we introduce BigCodeArena, an open human evaluation platform for 
  code generation back-ended with a comprehensive and on-the-fly execution environment. Built on top of Chatbot Arena, BigCodeArena features to 
  enable the execution of LLM-generated code and allow humans to interact with the execution process and outcomes. We collected over 14K raw 
  code-centric conversation sessions across 10 widely used LLMs, spanning 10 programming languages and 8 types of execution environments. Among 
  these conversations, we identify more than 4.7K multi-turn samples with pairwise human preference. Further analysis uncovers the underexplored 
  preferences of LLMs in fine-grained domains characterized by tasks, languages, and frameworks. To systematically examine code understanding and 
  generation capabilities of frontier LLMs, we curate two benchmarks based on the collected data, namely BigCodeReward and AutoCodeArena. For 
  BigCodeReward, we postprocess the 4.7K conversations and evaluate the consistency between reward models and human preference. The evaluation 
  shows that most LLMs have superior performance in judging coding preferences when the execution results are given. Inspired by the findings, 
  we propose AutoCodeArena, an automatic Elo rating benchmark designed to assess the coding quality of LLMs without humans. We find that proprietary 
  LLMs like GPT-5, Claude-Sonnet-4, and Claude-Opus-4 still lead the performance in code generation among the recent emerging models. To democratize 
  transparent evaluation of code generation in the wild, we aim to establish BigCodeArena as a long-term project.
</p>
