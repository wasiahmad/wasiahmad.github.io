---
title: "From SWE-ZERO to SWE-HERO: Execution-free to Execution-based Fine-tuning for Software Engineering Agents"
collection: publications
Authors: 'Nikolai Ludwig<sup>*</sup>, <b>Wasi Uddin Ahmad</b><sup>*</sup>, Somshubra Majumdar, and Boris Ginsburg.'
date: 04/2026
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2604.01496'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2604.01496' target="_blank">[Download Paper]</a>
<p align="justify">
We introduce SWE-ZERO to SWE-HERO, a two-stage SFT recipe that achieves state-of-the-art results on SWE-bench by distilling open-weight frontier 
  LLMs. Our pipeline replaces resource-heavy dependencies with an evolutionary refinement strategy: (1) SWE-ZERO utilizes large-scale, execution-free 
  trajectories to master code semantics and repository-level reasoning, and (2) SWE-HERO applies targeted, execution-backed refinement to transition 
  these semantic intuitions into rigorous engineering workflows. Our empirical results set a new benchmark for open-source models of comparable size. 
  We release a dataset of 300k SWE-ZERO and 13k SWE-HERO trajectories distilled from Qwen3-Coder-480B, alongside a suite of agents based on the 
  Qwen2.5-Coder series. Notably, SWE-HERO-32B achieves a 62.2% resolution rate on the SWE-bench Verified. Furthermore, despite being trained 
  exclusively on Python, our agents demonstrate robust zero-shot transferability on SWE-bench Multilingual, reaching 44.1% and confirming the 
  paradigm's generalizability across diverse languages.
</p>
