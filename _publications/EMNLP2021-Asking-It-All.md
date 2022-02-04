---
title: "Asking It All: Generating Contextualized Questions for any Semantic Role"
collection: publications
permalink: /publication/EMNLP2021-Asking-It-All
excerpt: "We introduce the task of role question generation, which, given a predicate mention and a passage, requires producing a set of questions asking about all possible semantic roles of the predicate. ... Unlike most existing approaches to question generation, our approach does not require conditioning on existing answers in the text."
date: 2021-11-01
venue: 'EMNLP'
paperurl: "https://aclanthology.org/2021.emnlp-main.108/"
citation: 
slides: "https://docs.google.com/presentation/d/1Y-tHQ5L0Y6xGG9S_8cWm58uPdSa4trtpIZ0jui1wSLk/edit?usp=sharing"
video: 
pdf: "https://aclanthology.org/2021.emnlp-main.108.pdf"
repo: "https://github.com/ValentinaPy/RoleQGeneration"
---


As a part of an ongoing project to tackle implicit predicate-argument relations with reading comprehension models, we faced a somewhat different challenge: how to write a question about a semantic role of interest without pre-specifying the answer, and even without knowing if the answer exists at all. By itself, this task is interesting to explore, as usual question-generation setups condition on the answer to produce the question, we condition on a concept. It enables the asker to ask about the desired piece of information without first locating the information, in accordance with a typical needs in information retrieval: Specify what you wish to know then go ahead and find it.  


**Abstract**

Asking questions about a situation is an inherent step towards understanding it. 
To this end, we introduce the task of role question generation, which, given a predicate mention and a passage, requires producing a set of questions asking about all possible semantic roles of the predicate. We develop a two-stage model for this task, which first produces a context-independent question prototype for each role and then revises it to be contextually appropriate for the passage.
Unlike most existing approaches to question generation, our approach does not require conditioning on existing answers in the text.
Instead, we condition on the type of information to inquire about, regardless of whether the answer appears explicitly in the text, could be inferred from it, or should be sought elsewhere.
Our evaluation demonstrates that we generate diverse and well-formed questions for a large, broad-coverage ontology of predicates and roles.

![Heuristically building training data for contextualization](/assets/contextualization.png)

[PDF]({{ page.pdf }}) [Slides]({{ page.slides }}) [Video]({{page.video}})