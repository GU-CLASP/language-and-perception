---
layout: page
title: Explainable multi-modal transformers
short_title: Explainability

---

## Goal

Explore the knowledge captured in uni-modal or multi-modal transformer-based language models. Look at how different modalities are fused (information fusion) in the transformer and how does it affect the grounding of modalities into one another. Also, examine how this knowledge can be explained or interpreted with either purely technical methods or analysis based on insights from cognitive science and related disciplines.

## Background

Transformers became a state-of-the-art method for handling many NLP tasks, including text-only (machine translation, sentiment analysis) and multi-modal problems (image captioning, visual question answering). Moreover, these models are superior to many other networks (e.g., LSTM), primarily due to their size and self-attention, which allows them to capture semantics on different levels.

However, it is unclear why transformers work so well for many NLP tasks. Although these networks are highly complex, they are less explainable than more traditional NLP approaches (grammars, formalisms). More recently, a lot of research has been focused on analysing what sort of linguistic knowledge is captured by transformers. So far, BERTology (a field about explaining how transformers learn) has mainly studied attention weights between linguistic input and outputs to the model. Also, probing and gradient-based analysis have been used to examine the impact on particular neurons/parts of the model. Understanding how learning happens in BERT-like models is beneficial for identifying problems such as different biases (e.g., gender, data) that occur very often.

## Problem description

### Model-based tasks

  - T1. Examine attention weights in the multi-modal transformer and inspect grounding of two modalities into one another, looking at each modality's impact on the task. For example, examine how much functional and perceptual knowledge is contained in a large trained transformer and how complete this knowledge is.
  - T2. Analyse gradients or use a probing classifier to inspect how the knowledge captured in large language models can be extracted. The focus here is on understanding what is missing in large language models and how this knowledge can be imported from other sources (e.g., other modalities, world knowledge).
  - T3. Develop linguistic test suits and cognitively inspired testing benchmarks and test language models for presence of specific knowledge based on models' performance on these suits (example: [Findings of ACL 2022 paper](https://aclanthology.org/2022.findings-acl.320.pdf)).

For examples of research in this direction, you can examine [one of our papers](https://iwcs2021.github.io/proceedings/mmsr/pdf/2021.mmsr-1.5.pdf) and [some other papers](https://aclanthology.org/2020.tacl-1.54/).


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
