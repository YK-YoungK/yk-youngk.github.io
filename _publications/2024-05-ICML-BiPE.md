---
title: "Two Stones Hit One Bird: Bilevel Positional Encoding for Better Length Extrapolation"
collection: publications
permalink: /publication/2024-05-ICML-BiPE
excerpt: 'This paper leverages the intrinsic segmentation of language sequences and design a new positional encoding method called Bilevel Positional Encoding (BiPE). This paper shows BiPE is more effective from both theoretical and empirical analysis.'
date: 2024-05-01
venue: 'ICML'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://yk-youngk.github.io/files/ICML-2024-BiPE-paper.pdf'
# citation: 'https://yk-youngk.github.io/files/ICML-2024-BiPE-bibtex.bib'
---

[Paper](https://yk-youngk.github.io/files/ICML-2024-BiPE-paper.pdf)
|
[Twitter](https://x.com/zhenyuhe00/status/1786012160256258367)
|
[Code](https://github.com/zhenyuhe00/BiPE)
|
[Citation](https://yk-youngk.github.io/files/ICML-2024-BiPE-bibtex.bib)

In this work, we leverage the intrinsic segmentation of language sequences and design a new positional encoding method called Bilevel Positional Encoding (BiPE). For each position, our BiPE blends an intra-segment encoding and an inter-segment encoding. The intra-segment encoding identifies the locations within a segment and helps the model capture the semantic information therein via absolute positional encoding. The inter-segment encoding specifies the segment index, models the relationships between segments, and aims to improve extrapolation capabilities via relative positional encoding. Theoretical analysis shows this disentanglement of positional information makes learning more effective. The empirical results also show that our BiPE has superior length extrapolation capabilities across a wide range of tasks in diverse text modalities.