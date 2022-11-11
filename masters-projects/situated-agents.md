---
layout: page
title: Situated interactive agents
short_title: Agents
---

## Goal

Explore how a situated agent can learn language through its interactions with other humans and with its environment.

## Background

Situated agents or robots must be able to interact with the physical environment that are located in with their conversational partners. Both linguistic and perceptual environments are contiously changing and therefore an agent must learn from its linguistic and perceptual observations. How are words grounded in perception and action? How can an agent learn incrementally? Since our time to train agents is limited: can information from other domains (for example, models trained on large corpora) be used as a background knowledge?

## Problem description

  - T1. Sensory observations of a robot may be incomplete due to errors that robot's sensors or actuators introduce or simply because the robot has not explored and mapped the entire world yet. Can a robot query a human about the missing knowledge linguistically? How can this information be used with the classification models of its perception and action?
  - T2. What are the interaction strategies in the tutor-robot scenario, how they can be implemented in the ML model and how effective they are?
  - T3. How can a pre-trained knowledge (for example, features trained with deep learning) from a large collection of image/RGB-D data) help the robot learn objects presented to them, and more successfully? What machine learning models should we use?
  - T4. How do situated agents ``acquire'' knowledge about the world and how do they keep learning continuously? In one of the project, we will look at how different word classes are learned with embodied agents. For more information and examples, read [Grounded language learning fast and slow](https://arxiv.org/pdf/2009.01719.pdf) and [Multi-agent cooperation and the emergence of (natural) language](https://arxiv.org/pdf/1612.07182.pdf).

These tasks can be explored in a real-life scenario with [our system based on the Kinect sensor](https://aclanthology.org/W17-0219/), a virtual environment/robot [Habitat AI](https://aihabitat.org) or, if you feel adventurous, the Unity game engine.

<iframe id="kmsembed-0_ab8jb62z" width="722" height="406" src="https://play.gu.se/embed/secure/iframe/entryId/0_ab8jb62z/uiConfId/23450401" class="kmsembed" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" referrerPolicy="no-referrer-when-downgrade" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="Kaltura Player"></iframe>

More recently, we published a paper with one of the students (Yasmeen Emampoor) on the role of visual modality in embodied question answering task, the task that is inherently interactive and involves navigation. The paper is available [here](https://github.com/GU-CLASP/embodied-qa/blob/main/papers/inlg-2022/paper.pdf).


## Recommended knowledge and skills

For students in Masters in Language Technology (MLT), the master thesis would build on the following courses

  - Computational semantics
  - Dialogue systems
  - Machine learning
  - AI: Cognitive systems

or equivalent knowledge and skills for external students.

A potential candidate should be comfortable in programming with Python, have a knowledge of Ubuntu/Linux command shell environment and occasionally be able to solve hardware problems with Kinect and possibly networking. However, help will be provided.


## Supervisors

Simon Dobnik and Nikolai Ilinykh
