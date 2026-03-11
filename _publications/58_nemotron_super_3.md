---
title: "Nemotron 3 Super: Open, Efficient Mixture-of-Experts Hybrid Mamba-Transformer Model for Agentic Reasoning"
collection: publications
Authors: 'NVIDIA'
date: 03/2026
venue: 'arXiv'
paperurl: 'https://research.nvidia.com/labs/nemotron/files/NVIDIA-Nemotron-3-Super-Technical-Report.pdf'
modelurl: 'https://huggingface.co/collections/nvidia/nvidia-nemotron-v3'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2512.20848' target="_blank">[Download Paper]</a><a href='https://huggingface.co/collections/nvidia/nvidia-nemotron-v3' target="_blank">[Download Models]</a>
<p align="justify">
We describe the pre-training, post-training, and quantization of Nemotron 3 Super, a 120 billion (active 12 billion) parameter hybrid 
  Mamba-Attention Mixture-of-Experts model. Nemotron 3 Super is the first model in the Nemotron 3 family to 1) be pre-trained in NVFP4, 2) leverage 
  LatentMoE, a new Mixture-of-Experts architecture that optimizes for both accuracy per FLOP and accuracy per parameter, and 3) includes MTP layers 
  for inference acceleration through native speculative decoding. We pre-trained Nemotron 3 Super on 25 trillion tokens, followed by post-training 
  using supervised fine-tuning (SFT) and reinforcement learning (RL). The final model supports up to 1M context length and achieves comparable 
  accuracy on common benchmarks, while also achieving up to 2.2× and 7.5× higher inference throughput compared to GPT-OSS-120B and Qwen3.5-122B, 
  respectively. Nemotron 3 Super datasets, along with the base, post-trained, and quantized checkpoints, are open-sourced on HuggingFace.
</p>
