---
title: "Nemotron 3.5 Super and Lightning: Open, Efficient Mixture-of-Experts Hybrid Mamba-Transformer Models for Agentic AI"
collection: publications
Authors: 'NVIDIA'
date: 10/2026
venue: 'NVIDIA Research Blog'
paperurl: 'https://research.nvidia.com/labs/nemotron/files/NVIDIA-Nemotron-3.5-Super-and-Lightning-Technical-Report.pdf'
modelurl: 'https://huggingface.co/collections/nvidia/nvidia-nemotron-v3'
excerpt: ''
---
---
<a href='https://research.nvidia.com/labs/nemotron/files/NVIDIA-Nemotron-3.5-Super-and-Lightning-Technical-Report.pdf' target="_blank">[Download Paper]</a><a href='https://huggingface.co/collections/nvidia/nvidia-nemotron-v3' target="_blank">[Download Models]</a>
<p align="justify">
We introduce Nemotron 3.5 Super and Nemotron 3.5 Lightning, open and efficient Mixture-of-Experts Hybrid Mamba-Transformer models designed for reasoning, long-context 
  understanding, and agentic workloads. Super is a 120B-parameter, 12B-active multimodal model, while Lightning is a smaller 30B-parameter, 3B-active text model; both designed 
  for efficient deployment. Both models combine large-scale distillation, long-context training, and native speculative decoding, while Super further incorporates Indic continued 
  pretraining and agentic software-engineering mid-training. We develop a comprehensive post-training pipeline spanning supervised fine-tuning and reinforcement learning (RLVR 
  and RLHF), complemented in Super by specialized teacher training and multiteacher on-policy distillation (MOPD). This transforms Super from a text-only base model into a 
  multimodal agent capable of reasoning over text, images, video, and interactive tool environments. We further explore test-time scaling through parallel agent execution and 
  self-verification. Across training and deployment, we jointly optimize capability and efficiency. Indic continued pretraining improves Indian-language benchmarks by up to 
  9.82 percentage points, while agentic mid-training strengthens software-engineering capabilities and robustness across agent harnesses. The post-trained Super model achieves 
  51.78% on SWE-bench Pro, surpassing Nemotron 3 Ultra despite using approximately 4.6× fewer active parameters. Post-training MTP boosting improves speculative decoding 
  acceptance length by up to 21.8% under probabilistic draft sampling, while NVFP4 quantization achieves 99.62% median accuracy recovery relative to BF16. Inference optimizations 
  enable up to 4,856 output tokens/s/GPU on GB200 while sustaining at least 50 tokens/s/user. Under the evaluated interactive agentic workload, NVFP4 achieves 2.43× the throughput 
  of BF16, while Nemotron 3.5 Super delivers 2.34× and 1.90× the throughput of Qwen3.5 and Qwen3.8 Flash-Next, respectively. We release base, BF16 post-trained, and 
  NVFP4-quantized model checkpoints, alongside standalone parallel speculative drafters (LiLiCorr, DFlash, and DSpark), with accompanying model cards, pretraining and 
  post-training datasets, cookbooks, and training recipes.
</p>
