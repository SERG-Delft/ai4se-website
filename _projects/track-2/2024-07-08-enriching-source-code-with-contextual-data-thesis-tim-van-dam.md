---
layout: project
title: "Enriching Source Code with Contextual Data for Code Completion Models"
tracks: [2]
image: "projects/track-2/tim-thesis-first-page.png"
publish_date: "8th of July 2024"
authors:
    - Tim van Dam
    - Maliheh Izadi
    - Arie van Deursen
    - Egor Bogomolov
publish-url: "https://repository.tudelft.nl/record/uuid:69c13738-0f23-42d5-845d-3312381e3b94"
artifact-url: ""
abstract: | 
    Transformer-based pre-trained models have recently achieved great results in solving many software engineering tasks including automatic code completion which is a staple in a developer’s toolkit. While many have striven to improve the code-understanding abilities of such models, the opposite – making the code easier to understand – has not been properly investigated. In this study, we aim to answer whether making code easier to understand through using contextual data improves the performance of pre-trained code language models for the task of code completion. We consider type annotations and comments as two common forms of additional contextual information that often help developers understand code better. For the experiments, we study code completion in two granularity levels; token and line completion and take three recent and large-scale language models for source code: UniXcoder, CodeGPT, and InCoder with five evaluation metrics. Finally, we perform the Wilcoxon Signed Rank test to gauge significance and measure the effect size. Contrary to our expectations, all models perform better if type annotations are removed (albeit the effect sizes are small). For comments, we find that the models perform better in the presence of multi-line comments (again with small effect sizes). Based on our observations, we recommend making proper design choices when training, fine-tuning, or simply selecting such models given the intended data and application. Better evaluations and multimodal techniques can also be further investigated to improve the practicality and accuracy of auto-completions.

---


