---
title: "Context Attentive Document Ranking and Query Suggestion"
collection: talks
type: "Conference Presentation"
permalink: /talks/2019-07-presentation-sigir
venue: "SIGIR 2019"
date: 2019-07-23
location: "Paris, France"
---

In this talk, I will introduce a Context Attentive Document Ranking and Query Suggestion Model based on a two-level hierarchical recurrent neural network to learn search context representation of individual queries, search tasks, and corresponding dependency structure.

[[Paper]](../files/publications/2019/context_attentive_ranking_and_suggestion.pdf)[[Code]](https://github.com/wasiahmad/context_attentive_ir)

======

<p align="justify">
  We present a context-aware neural ranking model to exploit users' on-task search activities and enhance retrieval performance. In particular, a two-level hierarchical recurrent neural network is introduced to learn search context representation of individual queries, search tasks, and corresponding dependency structure by jointly optimizing two companion retrieval tasks: document ranking and query suggestion. To identify variable dependency structure between search context and users' ongoing search activities, attention at both levels of recurrent states are introduced. Extensive experiment comparisons against a rich set of baseline methods and an in-depth ablation analysis confirm the value of our proposed approach for modeling search context buried in search tasks.
</p>
