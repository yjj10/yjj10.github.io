---
title: "Can We Separate 'What I See' from 'What I Infer'? Rethinking Hallucinations and Uncertainty in MLLMs with ECHO"
date: 2025-07-24 00:01:00 +0800
selected: true
pub: "AAAI 2026 (Under Review)"
pub_date: "2026"
abstract: >-
  Multimodal Large Language Models excel at generalizing across tasks, however, they face significant 
  challenges when visual information is missing or uncertain. In these cases, the models often rely 
  heavily on language, leading to "confident" outputs that are unsupported by visual evidence. This 
  reliance creates uncertainty in reasoning: How do these models reason when visual evidence is incomplete, 
  and can they express uncertainty in their inferences rather than fabricating overly confident responses? 
  We propose Embedded Counterfactual Hallucination Override (ECHO), a framework designed to help multimodal 
  models manage uncertainty when visual information is missing. ECHO operates in two stages: 
  (1) simulating missing visual information by replacing uncertain visual regions with learnable embeddings 
  to allow reasoning under uncertainty, and (2) quantifying inference uncertainty via a risk scoring mechanism 
  combining KL divergence and entropy. This enables the model to mitigate overconfident outputs in uncertain 
  situations and penalizes high-risk tokens during training, encouraging the model to adjust its confidence 
  when visual evidence is absent. Extensive experiments on benchmarks demonstrate that ECHO improves model 
  robustness, reduces overconfident inferences, enhances interpretability, and offers a lightweight, 
  deployable solution with minimal training cost. Positioned at the intersection of uncertainty quantification 
  and explainable AI, ECHO improves both the reliability and transparency of multimodal reasoning tasks.
cover: /assets/images/photos/echo.jpg
cover:          /assets/images/photos/echo.png
authors:
  - "Jianjiang Yang*"
  - Ziyan Huang
  - Da Peng
---
