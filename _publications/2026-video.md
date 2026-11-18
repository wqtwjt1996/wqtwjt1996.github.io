---
id:             2026-video
title:          "Transfer Once, Ask Locally: Compact Audio-Visual Memory for On-Device Question Answering"
authors:        
    - Me
    - Jihui 
    - Divya
    - Vishnu
    - Christopher
venue:          arXiv preprint.
year:           "2026-11"
thumbnail:      assets/publications/2026-video/title-image.png
bibtex: "@InProceedings{Wang_2026_Video,<br>&emsp;author = {Wang, Qitong and Jin, Jihui and Kothandaraman, Divya and Raj, Vishnu and Rasmussen, Christopher},<br>&emsp;title = {Transfer Once, Ask Locally: Compact Audio-Visual Memory for On-Device Question Answering},<br>&emsp;booktitle={arXiv preprint},<br>&emsp;year = {2026}<br>}"
links:
   paper:            https://arxiv.org/abs/2611.23085
   bibtex:           assets/publications/2026-video/ref.txt

layout: project_plus
short_title: Efficient Video Understanding
abstract: "Audio-visual question answering on lightweight user devices requires balancing speed, memory usage, privacy, and communication. One approach is to run audio-visual encoders on a server and a lightweight language decoder on the user device, keeping questions local while offloading media encoding. However, transferring and processing the full multimodal representation remains costly. We propose a training-free, query-agnostic token pruning framework that constructs a compact, reusable memory before transmission. We define video spatio-temporal blocks and aligned audio windows as players and estimate their importance through Monte Carlo Shapley valuation. We use an embedding coverage objective that combines query-independent utility with cross-modal redundancy calibration and rewards unimodal diversity through marginal coverage gains. We retain the original token embeddings of high-scoring players under a limited token budget and transfer the resulting memory once for reuse across subsequent local questions. Experiments on Video-MME, Daily-Omni, and Video-Holmes using video-SALMONN 2+ (3B) and video-SALMONN 2 Pro (4B) show that our method achieves the best or tied-best QA accuracy among the compared compression methods across all evaluated settings. On Daily-Omni with video-SALMONN 2+ (3B) at 80% pruning, our method improves accuracy by 12.86 to 14.62 percentage points over these methods while achieving the lowest device-side LLM prefill and decoding latency, with up to 1.92x decoding speedup at comparable embedding memory usage."
---
