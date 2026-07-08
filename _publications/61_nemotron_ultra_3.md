---
title: "Nemotron 3 Ultra: Open, Efficient Mixture-of-Experts Hybrid Mamba-Transformer Model for Agentic Reasoning"
collection: publications
Authors: 'NVIDIA'
date: 06/2026
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2606.15007'
modelurl: 'https://huggingface.co/collections/nvidia/nvidia-nemotron-v3'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2606.15007' target="_blank">[Download Paper]</a><a href='https://huggingface.co/collections/nvidia/nvidia-nemotron-v3' target="_blank">[Download Models]</a>
<p align="justify">
We introduce Nemotron 3 Ultra, a 550 billion total and 55 billion active parameter Mixture-of-Experts Hybrid Mamba-Attention language model. We pre-trained Nemotron 3 Ultra on 
  20 trillion text tokens, then extended the context length to 1M tokens, and post-trained using Supervised Fine Tuning (SFT), Reinforcement Learning (RL), and Multi-teacher 
  On-Policy Distillation (MOPD). Nemotron 3 Ultra is our most capable model yet, employing multiple key technologies - LatentMoE, Multi Token Prediction (MTP), NVFP4 pre-training, 
  multi-environment RLVR, MOPD, and reasoning budget control. Nemotron 3 Ultra achieves up to ~6x higher inference throughput as compared to state-of-the-art publicly available 
  LLMs while attaining on-par accuracy. The state-of-the-art accuracy, high inference throughput, and 1M token context length make Nemotron 3 Ultra ideal for long-running 
  autonomous agentic tasks. We open-source the base, post-trained, and quantized checkpoints, along with the training data and recipe on HuggingFace.
</p>
