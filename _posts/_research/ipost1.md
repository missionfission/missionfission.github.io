---
title: "Reusable Code Mining from Github"
date: 2199-01-01
collection: posts
permalink: /posts/2012/08/blog-post-4/
tags:
  - cool posts
---

<!-- This post will show up by default. To disable scheduling of future posts, edit `config.yml` and set `future: false`.  -->

Models that map natural language (NL) to source code in general purpose languages such as Java, Python, and SQL find utility amongst two main audiences viz. developers who can manipulate the generated code, and non-expert users who directly see the output of execution. Developing these models is challenging because of contextual dependencies of the target code, the lack of alignment between NL and code tokens, syntactic and semantic requirements of the target code, and the prohibitively expensive cost of annotating training data. The first part of my talk will focus on contextual code generation from NL for developers. I will present ways to obtain inexpensive training datasets from large online code repositories, followed by methods to incorporate contextual awareness in syntax-guided neural models to improve performance on the task. Next, I will describe techniques to extract and use programmatic idioms to significantly speed up training and scale our models. The second part of my talk will focus on building NL interfaces for querying databases using SQL, for non-expert users. I will describe methods to build deep learning models that improve in performance over time by leveraging user feedback and annotations obtained from crowd programmers. I will conclude by presenting ideas for extending our NL to code models, as well as several complementary tasks relating to interactivity and explainability.
