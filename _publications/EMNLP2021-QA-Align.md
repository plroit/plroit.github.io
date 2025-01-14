---
title: "QA-Align: Representing Cross-Text Content Overlap by Aligning Question-Answer Propositions"
collection: publications
permalink: /publication/EMNLP2021-QA-Align
excerpt: "In order to explicitly represent content overlap, we propose to align predicate-argument relations across texts, providing a potential scaffold for information consolidation. "
date: 2021-11-01
venue: 'EMNLP'
paperurl: 
citation: 
slides: "https://docs.google.com/presentation/d/1A4G_4rTioXO4_Fuj45UE_EmYF9roJz4tRACfALcAa5g/edit?usp=sharing"
video: 
pdf: 
repo: "https://github.com/DanielaBWeiss/QA-ALIGN" 
---
**Abstract**
Multi-text applications, such as multi-document summarization, are typically required to model redundancies across related texts.    
Current methods confronting
consolidation struggle to fuse overlapping information.
In order to explicitly represent content overlap, we propose to align predicate-argument relations across texts, providing a potential scaffold for information consolidation. 
We go beyond clustering coreferring  
mentions, and instead model overlap with respect to redundancy at a propositional level, rather than merely detecting shared referents. Our setting exploits QA-SRL, utilizing question-answer pairs to capture predicate-argument relations, facilitating laymen annotation of cross-text alignments.
We employ crowd-workers for constructing a dataset of QA-based alignments,
and present a baseline QA alignment model trained over our dataset.
Analyses show that our new task is semantically challenging, capturing content overlap
beyond lexical similarity and complements cross-document coreference with proposition-level links, offering potential use for downstream tasks.
[PDF]({{ page.pdf }}) [Slides]({{ page.slides }}) [Video]({{page.video}})