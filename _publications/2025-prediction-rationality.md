---
id:             2025-prediction-rationality
title:          "Beyond Accuracy: On the Effects of Fine-tuning Towards Vision-Language Model's Prediction Rationality"
authors:        
    - Me 
    - Tang
    - Kien
    - Xi
venue:          Association for the Advancement of Artificial Intelligence (AAAI), Philadelphia, Pennsylvania, USA, 2025.
year:           "2025-02"
thumbnail:      assets/publications/2025-prediction-rationality/title-image.png
overview:       assets/publications/2025-prediction-rationality/overview.png
overview_text:  "In this paper, we propose two new evaluation metrics to evaluate the prediction rationality of Vision-Language Models (VLMs): whether the VLM predictions are both correct and based on valid evidence. We evaluate with two criteria in mind: (1) A trustworthy Vision-Language Model (VLM) should not produce instances of invalid evidence among samples with correct predictions. (2) When focusing on the correct predicted objects, a reliable VLM should leverage such valid evidence to achieve correct predictions. As a result, we achieve four scenarios: RR, RW, WR, and WW that are used to formalize our proposed two novel evaluation metrics: PT and IR."
bibtex: "@InProceedings{Wang_2025_Rationale,<br>&emsp;author    = {Wang, Qitong and Li, Tang and Nguyen, Kien X. and Peng, Xi},<br>&emsp;title     = {Beyond Accuracy: On the Effects of Fine-tuning Towards Vision-Language Model's Prediction Rationality},<br>&emsp;booktitle = {In Proceedings of the Association for the Advancement of Artificial Intelligence (AAAI)},<br>&emsp;month     = {February},<br>&emsp;year      = {2025},<br>}"
links:
   paper:      https://arxiv.org/abs/2412.13333
   code:       https://github.com/deep-real/vlm-pred-rationality
   bibtex:     assets/publications/2025-prediction-rationality/ref.txt
results:
   text1:      Evaluations with PT
   img1:       assets/publications/2025-prediction-rationality/res/1.png
   text2:      Evaluations with IR
   img2:       assets/publications/2025-prediction-rationality/res/2.png
   text3:      Visualizations
   img3:       assets/publications/2025-prediction-rationality/res/3.png
layout: project_plus
short_title: Prediction Rationality
video_embed: https://www.youtube.com/embed/pIrUZuisB_E?si=tegSUttZfS1sbVpA
abstract:  "Vision-Language Models (VLMs), such as CLIP, have already seen widespread applications. Researchers actively engage in further fine-tuning VLMs in safety-critical domains. In these domains, prediction rationality is crucial: the prediction should be correct and based on valid evidence. Yet, for VLMs, the impact of fine-tuning on prediction rationality is seldomly investigated. To study this problem, we proposed two new metrics called Prediction Trustworthiness and Inference Reliability. We conducted extensive experiments on various settings and observed some interesting phenomena. On the one hand, we found that the well-adopted fine-tuning methods led to more correct predictions based on invalid evidence. This potentially undermines the trustworthiness of correct predictions from fine-tuned VLMs. On the other hand, having identified valid evidence of target objects, fine-tuned VLMs were more likely to make correct predictions. Moreover, the findings are also consistent under distributional shifts and across various experimental settings. We hope our research offer fresh insights to VLM fine-tuning."
---