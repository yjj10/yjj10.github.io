---
title: "CAMA: Enhancing Multimodal In-Context Learning with Context-Aware Modulated Attention"
date: 2025-05-23 00:01:00 +0800
selected: true
pub: "AAAI 2026 (Under Review)"
pub_date: "2026"
abstract: >-
  Multimodal in-context learning (ICL) is emerging as a key capability that enables large vision-language 
  models (LVLMs) to adapt to novel tasks without parameter updates, expanding their utility across 
  various real-world applications. However, ICL remains unstable, even with well-matched in-context 
  demonstrations (ICDs), suggesting that LVLMs struggle to fully utilize the provided context. While existing 
  efforts focus on prompt engineering or post-hoc logit calibration, we instead investigate the underlying 
  attention dynamics to overcome LVLMs' inherent limitations. To bridge the gap, we propose 
  Context-Aware Modulated Attention (CAMA), a plug-and-play and training-free method that dynamically 
  modulates LVLM's attention logits based on the input in-context sequence. CAMA employs a two-stage 
  attention modulation to address both identified deficits, enhancing the focus on semantically significant 
  tokens, particularly visual ones. Across four LVLMs and seven benchmarks, CAMA consistently 
  outperforms vanilla models and baselines, demonstrating great effectiveness and generalization. It can 
  also activate the desired effects of prompt engineering methods and remains robust under diverse 
  sequence configurations. Thus, CAMA paves the way for deeper explorations of attention dynamics to 
  advance multimodal reasoning.
cover: /assets/images/photos/cama.png
authors:
  - "Yanshu Li* (co-first author)"
  - "Jianjiang Yang* (co-first author)"
  - Ziteng Yang
  - Bozheng Li
  - Hongyang He
  - Zhengtao Yao
  - Ligong Han
  - Yingjie Victor Chen
  - Songlin Fei
  - Dongfang Liu
  - Ruixiang Tang
links:
  Paper (arXiv): https://arxiv.org/abs/2505.17097
---
