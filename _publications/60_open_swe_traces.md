---
title: "Open-SWE-Traces: Advancing Dual-Mode Multilingual Distillation for Software Engineering Agents"
collection: publications
Authors: '<b>Wasi Uddin Ahmad</b>, Nikolai Ludwig, Somshubra Majumdar, and Boris Ginsburg.'
date: 06/2026
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/?'
dataurl: 'https://huggingface.co/datasets/nvidia/Open-SWE-Traces'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/?' target="_blank">[Download Paper]</a><a href='https://huggingface.co/collections/nvidia/open-swe-traces' target="_blank">[Models and Datasets]</a>
<p align="justify">
The path toward autonomous software engineering is currently bottlenecked by a severe deficit of diverse, large-scale trajectory data. We address this by introducing OPEN-SWETRACES, an expansive dataset of 207,489 agentic trajectories 
  spanning nine programming languages (Python, Go, TS, JS, Rust, Java, PHP, C, C++). Sourced from 20,000 real-world PRs via OpenHands and SWE-agent harnesses, the dataset utilizes a hybrid-reasoning synthesis: Minimax-M2.5 generates 
  trajectories with explicit "thinking" processes, while Qwen3.5-122B provides high-quality "non-thinking" traces. Filtered for permissive licenses (MIT, Apache, BSD) from SWE-rebench-V2, this data facilitates the training of models 
  capable of long-horizon reasoning. We validate the dataset by fine-tuning the Qwen3-30B-A3B series (Thinking, Coder, and Instruct). The best performing model achieves resolve rates of 61.7% on SWE-bench Verified, 57.1% on SWE-bench 
  Multilingual, and 36.8% on SWEbench Pro. These results establish OPEN-SWETRACES as a premier resource for distilling human-level software engineering capabilities into efficient, open-source agentic LLMs.
</p>
