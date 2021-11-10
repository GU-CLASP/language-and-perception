---
layout: page
title: Reference and co-reference resolution in visual dialogue
short_title: (Co-)reference
permalink: /masters-projects/co-reference/
---

## Goal

The goal of this project is to model reference and co-reference resolution in visual dialogue by building upon the existing work on co-reference resolution in the document/textual domain.

## Background

Situated dialogue involves language and vision. An important aspect of processing situated dialogue is to resolve the reference of linguistic expressions. The challenging aspect is that descriptions are local to the current dialogue and visual context of the conversation [1] and that not all information is expressed linguistically as a lot of meaning can be recovered from the joint visual and dialogue attention. Co-reference resolution has been studied and modelled extensively in the textual domain where the scope of the processing co-reference is within a document [2]. Robust co-reference resolution for dialogue systems is a very much needed task but using standard textual co-reference tools in this domain presents several challenges and open questions [3].

## Problem description

  - T1. Extend the Cups corpus [4] by collecting data on Mechanical Turk.
  - T2. Annotate the corpus with co-reference chains either (a) manually or (b) through Mechanical Turk.
  - T3. Depending on the previous steps, for (a) do a corpus and statistical feature analysis of the annotations in relation to their predictability of co-reference, or for (b) train a supervised text and vision classification model for co-reference resolution. Alternatively, you can also start with the existing visual dialogue corpora.
  - T4. Analyse the coreference in these corpora and compare it with the Cups corpus.
  - T5. Explore deep learning models for co-reference on these corpora [5] and suggest improvements inspired by the earlier work on situated dialogue [6].


## Recommended knowledge and skills

For students in Masters in Language Technology (MLT), the master thesis would build on courses such as (i) Natural Language Processing, (ii) Computational Semantics, (iii) Machine Learning, and (iv) Embodied and situated language processing/Artificial Intelligence: Cognitive systems or equivalent. For other students, experience with (i) Language Technology, (ii) Machine Learning, (iii) Computer Vision, (vi) Robotics, and (vii) Cognitive Science or equivalent is useful. A potential candidate should be comfortable in programming with Python, machine learning and text and image processing tools and techniques.

## Supervisors

Simon Dobnik and Sharid Loáiciga


## Literature / previous work

  1. H. H. Clark and D. Wilkes-Gibbs. Referring as a collaborative process. Cognition, 22(1):1–39, 1986.
  2. M. Poesio, R. Stuckardt, and Y. Versley, editors. Anaphora resolution: algorithms, resources, and applications. Theory and Applications of Natural Language Processing. Springer, Berlin Heidelberg, 2016.
  3. S. Dobnik and S. Loáiciga. On visual coreference chains resolution. In Extended abstracts accepted for Seventh Swedish Language Technology Conference (SLTC-2018), pages 1–4, Stockholm, Sweden, November 7–9 2018.
  4. S. Dobnik, C. Howes, and J. D. Kelleher. Changing perspective: Local alignment of reference frames in dialogue. In C. Howes and S. Larsson, editors, Proceedings of goDIAL – Semdial 2015: The 19th Workshop on the Semantics and Pragmatics of Dialogue, pages 24–32, Gothenburg, Sweden, 24–26th August 2015.
  5. S. Kottur, J. M. Moura, D. Parikh, D. Batra, and M. Rohrbach. Visual coreference resolution in visual dialog using neural module networks. In Proceedings of the European Conference on Computer Vision (ECCV), pages 153–169, 2018.
  6. J. D. Kelleher, F. J. Costello, and J. van Genabith. Dynamically structuring updating and interrelating representations of visual and linguistic discourse. Artificial Intelligence, 167:62–102, 2005.
