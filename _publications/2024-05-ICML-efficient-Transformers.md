---
title: "Do Efficient Transformers Really Save Computation?"
collection: publications
permalink: /publication/2024-05-ICML-efficient-Transformers
excerpt: 'This paper investigates the expressive power of some efficient Transformer variants on reasoning tasks, showing they have no complexity gain comparing to standard Transformers on general reasoning tasks. This paper also investigates how locality can boost the efficiency of those efficient Transformers variants and reduce the computational cost.'
date: 2024-05-02
venue: 'ICML'
# slidesurl: 'https://yk-youngk.github.io/files/slides1.pdf'
paperurl: 'https://yk-youngk.github.io/files/ICML-2024-efficient-Transformers-paper.pdf'
citation: 'https://yk-youngk.github.io/files/ICML-2024-efficient-Transformers-bibtex.bib'
---

[Twitter](https://x.com/bohang_zhang/status/1763584750953050392)

As transformer-based language models are trained on increasingly large datasets and with vast numbers of parameters, finding more efficient alternatives to the standard Transformer has become very valuable. While many efficient Transformers and Transformer alternatives have been proposed, none provide theoretical guarantees that they are a suitable replacement for the standard Transformer. This makes it challenging to identify when to use a specific model and what directions to prioritize for further investigation. In this paper, we aim to understand the capabilities and limitations of efficient Transformers, specifically the Sparse Transformer and the Linear Transformer. We focus on their reasoning capability as exhibited by Chain-of-Thought (CoT) prompts and follow previous works to model them as Dynamic Programming (DP) problems. Our results show that while these models are expressive enough to solve general DP tasks, contrary to expectations, they require a model size that scales with the problem size. Nonetheless, we identify a class of DP problems for which these models can be more efficient than the standard Transformer. We confirm our theoretical results through experiments on representative DP tasks, adding to the understanding of efficient Transformers' practical strengths and weaknesses.