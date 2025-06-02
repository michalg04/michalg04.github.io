---
title: "Pixels Versus Priors: Controlling Knowledge Priors in Vision-Language Models through Visual Counterfacts"
author: "Michal Golovanevsky, William Rudman, Michael Lepori, Amir Bar, Ritambhara Singh, Carsten Eickhoff"
collection: publications
permalink: /publication/2025-05-01-pixels_vs_priors
excerpt: ''
date: 2025-05-01
venue: 'Journal of the American Medical Informatics Association, Volume 29, Issue 12'
paperurl: 'https://arxiv.org/abs/2505.17127'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Multimodal Large Language Models (MLLMs) perform well on tasks such as visual question answering, but it remains unclear whether their reasoning relies more on memorized world knowledge or on the visual information present in the input image. To investigate this, we introduce Visual CounterFact, a new dataset of visually-realistic counterfactuals that put world knowledge priors (e.g, red strawberry) into direct conflict with visual input (e.g, blue strawberry). Using Visual CounterFact, we show that model predictions initially reflect memorized priors, but shift toward visual evidence in mid-to-late layers. This dynamic reveals a competition between the two modalities, with visual input ultimately overriding priors during evaluation. To control this behavior, we propose Pixels Versus Priors (PvP) steering vectors, a mechanism for controlling model outputs toward either world knowledge or visual input through activation-level interventions. On average, PvP successfully shifts 92.5% of color and 74.6% of size predictions from priors to counterfactuals. Together, these findings offer new tools for interpreting and controlling factual behavior in multimodal models.

[Download paper here](https://arxiv.org/abs/2505.17127)

<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->