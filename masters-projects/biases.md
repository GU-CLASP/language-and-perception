---
layout: page
title: Biases, ethics and (multi-modal) NLP
short_title: Bias, ethics, multi-modality

---

## Goal

Develop benchmarks to evaluate social, gender and racial biases in multi-modal tasks such as image captioning and visual question answering.
Analyse and evaluate language models for biases related to misrepresented groups.
Critically examine the issue of ethics and creativity, e.g. generation of images from texts (e.g., DALL-E).
Explore biases in generative text-only models and whether these models show any reasoning capabilities (e.g., GPT-2).
On the other hand, look at the biases related to data and whether models amplify such biases.

## Background

AI has become a prominent part of our everyday life.
We play around with image description systems, generate texts, generate new images that never existed before.
But only recently we started asking all the important questions such as whether these systems behave like humans and whether what they generate is (ethically) acceptable.

The problem of bias is very vast: the problem can be in the dataset distribution, model structure, and even human biases collected from participants who took part in the dataset creation.
Here we offer a number of different takes on the problem of bias and whether models amplify it.


## Problem description

### Model-based tasks

  - T1. Biases in datasets. These biases are related to label distrubution, sampling from datasets and type of situations such datasets cover. The focus is on measuring whether models are affected by such biases in any way.
  - T2. Biases in models. How do different models learn from different input features? Is there a reason to use one-stream transformer and not a two-stream transformer for a specific task? Can we explain what these models learn through the lens of cognitive science?
  - T3. Societal biases. Can language models encode sensitive information and reveal it when used in sensitive situations?
  - T4. Creativity and reasoning. Can (multi-modal) langugae models reason about things they produce or generate? Is there an understanding of the image that is generated, e.g. art? What about text understanding on the global discourse level?

For examples of research in this direction, you can look at many of our papers (some of them were written with students) and others:
- [Generating Descriptions of Human Faces](https://aclanthology.org/2022.pvlam-1.5.pdf)
- [Can embodied agents use vision in the Embodied Question Answering task?](https://github.com/GU-CLASP/embodied-qa/blob/main/papers/inlg-2022/paper.pdf)
- [Understanding and Evaluating Racial Biases in Image Captioning](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhao_Understanding_and_Evaluating_Racial_Biases_in_Image_Captioning_ICCV_2021_paper.pdf)
- [Quantifying Societal Bias Amplification in Image Captioning](https://openaccess.thecvf.com/content/CVPR2022/papers/Hirota_Quantifying_Societal_Bias_Amplification_in_Image_Captioning_CVPR_2022_paper.pdf)
- [Hierarchical learning in multi-modal transformers](https://www.frontiersin.org/articles/10.3389/frai.2021.767971/full)


## Recommended knowledge and skills

For students in Masters in Language Technology (MLT), the master thesis would build on the following courses

  - Computational semantics
  - Dialogue systems
  - Machine learning
  - AI: Cognitive systems

or equivalent knowledge and skills for external students.

A potential candidate should be comfortable in programming with Python, machine learning and text and image processing tools and techniques.


## Supervisors

Simon Dobnik and Nikolai Ilinykh
