---
title: "Asking It All: Generating Contextualized Questions for any Semantic Role"
collection: publications
permalink: /publication/EMNLP2021-Asking-It-All
excerpt: "We introduce the task of role question generation, which, given a predicate mention and a passage, requires producing a set of questions asking about all possible semantic roles of the predicate. ... Unlike most existing approaches to question generation, our approach does not require conditioning on existing answers in the text."
date: 2021-11-01
venue: 'EMNLP'
paperurl: "https://arxiv.org/abs/2109.04832"
citation: 
slides: 
video: 
pdf: "https://arxiv.org/pdf/2109.04832.pdf"
repo: "https://github.com/ValentinaPy/RoleQGeneration"
---
**Abstract**
Asking questions about a situation is an inherent step towards understanding it. 
To this end, we introduce the task of role question generation, which, given a predicate mention and a passage, requires producing a set of questions asking about all possible semantic roles of the predicate. We develop a two-stage model for this task, which first produces a context-independent question prototype for each role and then revises it to be contextually appropriate for the passage.
Unlike most existing approaches to question generation, our approach does not require conditioning on existing answers in the text.
Instead, we condition on the type of information to inquire about, regardless of whether the answer appears explicitly in the text, could be inferred from it, or should be sought elsewhere.
Our evaluation demonstrates that we generate diverse and well-formed questions for a large, broad-coverage ontology of predicates and roles.

[PDF]({{ page.pdf }}) [Slides]({{ page.slides }}) [Video]({{page.video}})