---
title: "CATP: Contextually Adaptive Token Pruning for Efficient and Enhanced Multimodal In-Context Learning"
date: 2025-08-23 00:01:00 +0800
selected: true
pub: "AAAI 2026 (Under Review)"
pub_date: "2026"
abstract: >-
  Modern large vision-language models (LVLMs) convert each input image into a large set of tokens, 
  far outnumbering the text tokens. Although this improves visual perception, it introduces severe 
  image token redundancy. Because image tokens carry sparse information, many add little to reasoning, 
  yet greatly increase inference cost. The emerging image token pruning methods tackle this issue by 
  identifying the most important tokens and discarding the rest. These methods can raise efficiency with 
  only modest performance loss. However, most of them only consider single-image tasks and overlook 
  multimodal in-context learning (ICL), where redundancy is greater and efficiency is more critical. 
  Redundant tokens weaken the advantage of multimodal ICL for rapid domain adaptation and cause 
  unstable performance. Applying existing pruning methods in this setting leads to large accuracy drops, 
  exposing a clear gap and the need for new techniques. Thus, we propose Contextually Adaptive Token 
  Pruning (CATP), a training-free pruning method targeted at multimodal ICL. CATP consists of two stages 
  that perform progressive pruning to fully account for the complex cross-modal interactions in the input 
  sequence. After removing 77.8% of the image tokens, CATP produces an average performance gain of 
  0.6% over the vanilla model on four LVLMs and eight benchmarks, exceeding all baselines remarkably. 
  Meanwhile, it effectively improves efficiency by achieving an average reduction of 10.78% in inference 
  latency. CATP enhances the practical value of multimodal ICL and lays the groundwork for future progress 
  in interleaved image-text scenarios.
cover: /assets/images/photos/catp.png
authors:
  - "Yanshu Li* (co-first author)"
  - "Jianjiang Yang* (co-first author)"
  - Zhennan Shen
  - Ligong Han
  - Haoyan Xu
  - Ruixiang Tang
links:
  Paper (arXiv): https://arxiv.org/abs/2508.07871
---
