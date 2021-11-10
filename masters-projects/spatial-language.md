---
layout: page
title: Computational modelling of spatial language interpretation and generation
short_title: Spatial
permalink: /masters-projects/spatial-language/
---

## Goal

Explore a topic within natural language generation and interpretation of referring expressions.

## Background

The development of situated systems such as robots, virtual assistants, and geographic information systems is heavily dependent on the existence of adequate models of spatial language in order to allow users to interact with these systems, especially when communication through existing user interfaces is infeasible or inconvenient.

While early models of semantics of spatial description relied on geometrically motivated formal representations [1,4], it is now widely recognised that spatial term meaning is also dependent on functional [2,5,6] and pragmatic features [3,7,8,9]. (By functional knowledge we mean the knowledge about the objects involved and interaction between them.) Consequently, representations of spatial term semantics must accommodate geometric, functional and pragmatics aspects of situated meaning.


## Problem description

  - T1. Learning of spatial relations between objects on a table in interaction with humans in the Kille scenario [10] that the system also takes into account non-geometric features: dialogue for frame of reference negotiation and properties of objects.
  - T2. Extension of the work in [5,6,11,12] which aims to identify automatically from corpus of textual image descriptions sensitivity of spatial relations to different kinds of knowledge: geometric (where) or functional (what). Can similar prediction be made from (visual) image data?
  - T3. Using a virtual environment such as Unity or HabitatAI which contains models of objects and their affordances and allows running simulations of object interactions, can we teach the system how to "put the mug on the table" and "put the mug on the shelf"? Notice that in both cases the final location of the mug is highly dependent on the type of the object involved.
  - T4. Generating route descriptions in a complex building/virtual environment. How to generate route descriptions that provide the right kind of information so that a person finds the objects or location referred to?
  - T5. An extension of the Cups dataset and a computational model of spatial perspective taking [8].
  - T6. How are spatial relations learned by vision and language neural models in image captions [13,14]?


## Recommended knowledge and skills

For students in Masters in Language Technology (MLT), the master thesis would build on courses such as (i) Computational Semantics, (ii) Dialogue systems, (iii) Machine Learning, and (iv) Embodied and situated language processing or equivalent. For other students, experience with (i) Language Technology, (ii) Machine Learning, (iii) Computer Vision, (vi) Robotics, and (vii) Cognitive Science or equivalent is useful. A potential candidate should be comfortable in programming with Python, machine learning and text and image processing tools and techniques.

## Supervisors

Simon Dobnik and Nikolai Ilinykh


## Literature / previous work

  1. G. D. Logan and D. D. Sadler. A computational analysis of the apprehension of spatial relations. In P. Bloom, M. A. Peterson, L. Nadel, and M. F. Garrett, editors, Language and Space, pages 493–530. MIT Press, Cambridge, MA, 1996.
  2. K. R. Coventry, M. Prat-Sala, and L. Richards. The interplay between geometry and function in the apprehension of Over, Under, Above and Below. Journal of Memory and Language, 44(3):376–398, 2001.
  3. M. E. Watson, M. J. Pickering, and H. P. Branigan. Alignment of reference frames in dialogue. In Proceedings of the 26th Annual Conference of the Cognitive Science Society, Chicago, USA, 2004.
  4. S. Dobnik. Teaching mobile robots to use spatial words. PhD thesis, University of Oxford: Faculty of Linguistics, Philology and Phonetics and The Queen’s College, Oxford, United Kingdom, September 4 2009. pdf.
  5. S. Dobnik and J. D. Kelleher. Towards an automatic identification of functional and geometric spatial prepositions. In Proceedings of PRE-CogSsci 2013: Production of referring expressions – bridging the gap between cognitive and computational approaches to reference, pages 1–6, Berlin, Germany, 31 July 2013.
  6. S. Dobnik and J. D. Kelleher. Exploration of functional semantics of prepositions from corpora of descriptions of visual scenes. In Proceedings of the Third V&L Net Workshop on Vision and Language, pages 33–37, Dublin, Ireland, August 2014. Dublin City University and the Association for Computational Linguistics.
  7. S. Dobnik, J. D. Kelleher, and C. Koniaris. Priming and alignment of frame of reference in situated conversation. In V. Rieser and P. Muller, editors, Proceedings of DialWatt – Semdial 2014: The 18th Workshop on the Semantics and Pragmatics of Dialogue, pages 43–52, Edinburgh, 1–3 September 2014.
  8. S. Dobnik, C. Howes, and J. D. Kelleher. Changing perspective: Local alignment of reference frames in dialogue. In C. Howes and S. Larsson, editors, Proceedings of goDIAL – Semdial 2015: The 19th Workshop on the Semantics and Pragmatics of Dialogue, pages 24–32, Gothenburg, Sweden, 24–26th August 2015.
  9. S. Dobnik and A. Åstbom. (Perceptual) grounding as interaction. In V. Petukhova and Y. Tian, editors, Proceedings of Saardial – Semdial 2017: The 21st Workshop on the Semantics and Pragmatics of Dialogue, pages 17–26, Saarbrücken, Germany, August 15–17 2017.
 10. S. Dobnik and E. de Graaf. KILLE: a framework for situated agents for learning language through inter- action. In J. Tiedemann, editor, Proceedings of the 21st Nordic Conference on Computational Linguistics (NoDaLiDa), volume 131 of Link ̈oping Electronic Conference Proceedings and NEALT Proceedings Series Vol. 29, pages 1–10, Gothenburg, Sweden, 22–24 May 2017. Northern European Association for Language Technology (NEALT), Link ̈oping University Electronic Press.
 11. S. Dobnik, M. Ghanimifard, and J. D. Kelleher. Exploring the functional and geometric bias of spatial relations using neural language models. In Proceedings of the First International Workshop on Spatial Language Understanding (SpLU 2018) at NAACL-HLT 2018, pages 1–11, New Orleans, Louisiana, USA, June 6 2018. Association for Computational Linguistics.
 12. M. Ghanimifard and S. Dobnik. What a neural language model tells us about spatial relations. In A. Bhatia, Y. Bisk, P. Kordjamshidi, and J. Thomason, editors, Proceedings of the Combined Workshop on Spatial Language Understanding (SpLU) and Grounded Communication for Robotics (RoboNLP), pages 71–81, Minneapolis, Minnesota, USA, 6 June 2019. North American Chapter of the Association for Computational Linguistics: Human Language Technologies (NAACL-HLT 2019), Association for Computational Linguistics.
 13. M. Ghanimifard and S. Dobnik. Knowing when to look for what and where: Evaluating generation of spatial descriptions with adaptive attention. In L. Leal-Taix ́e and S. Roth, editors, Computer Vision – ECCV 2018 Workshops. ECCV 2018, volume 11132 of Lecture Notes in Computer Science (LNCS), pages 1–9, Proceedings of the Workshop on Shortcomings in Vision and Language (SiVL), ECCV 2018, Munich, Germany, 2018. Springer, Cham.
 14. M. Ghanimifard and S. Dobnik. What goes into a word: generating image descriptions with top-down spatial knowledge. In K. van Deemter, C. Lin, and H. Takamura, editors, Proceedings of the 12th International Conference on Natural Language Generation (INLG-2019), pages 1–15, Tokio, Japan, 29 October – 1 November 2019. Association for Computational Linguistics.
