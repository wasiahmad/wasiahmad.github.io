---
title: "Text2App: A Framework for Creating Android Apps from Text Descriptions"
collection: publications
Authors: 'Masum Hasan, Kazi Sajeed Mehrab, Baishakhi Ray,<b>Wasi Ahmad</b>, and Rifat Shahriyar.'
date: 04/2021
venue: 'Arxiv'
paperurl: 'https://arxiv.org/abs/2104.08301'
codeurl: 'https://github.com/Masum06/Text2App'
demourl: 'https://www.youtube.com/watch?v=Wr2TMuexkq8'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2103.06333.pdf' target="_blank">[Download Paper]</a><a href='https://github.com/wasiahmad/PLBART' target="_blank">[Source Code]</a>

<p align="justify">
We present Text2App -- a framework that allows users to create functional Android applications from natural language specifications. The conventional method of 
source code generation tries to generate source code directly, which is impractical for creating complex software. We overcome this limitation by transforming 
natural language into an abstract intermediate formal language representing an application with a substantially smaller number of tokens. The intermediate formal 
representation is then compiled into target source codes. This abstraction of programming details allows seq2seq networks to learn complex application structures 
with less overhead. In order to train sequence models, we introduce a data synthesis method grounded in a human survey. We demonstrate that Text2App generalizes 
well to unseen combination of app components and it is capable of handling noisy natural language instructions. We explore the possibility of creating applications 
from highly abstract instructions by coupling our system with GPT-3 -- a large pretrained language model. The source code, a ready-to-run demo notebook, and a 
demo video are publicly available at <a href='https://text2app.github.io' target="_blank">https://text2app.github.io/</a>.
</p>
