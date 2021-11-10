---
layout: page
title: Computational modelling of spatial descriptions
short_title: Spatial

---

## Goal

Explore a topic within natural language generation and interpretation of referring expressions with a particular emphasis on spatial relations such as "the red cup on the shelf", "a skateboarder is jumping over a fire hydrant" or "go down to the end of the corridor until the bookshelf and then turn right".

## Background

The development of situated systems such as robots, virtual assistants, and geographic information systems is heavily dependent on the existence of adequate models of spatial language in order to allow users to interact with these systems, especially when communication through existing user interfaces is infeasible or inconvenient.

While early models of semantics of spatial description relied on geometrically motivated formal representations, it is now widely recognised that spatial term meaning is also dependent on functional and pragmatic features. By functional knowledge we mean the knowledge about the objects involved and interaction between them and by pragmatic knowledge we mean how much of the meaning is contextually negotiated, for example in terms of the spatial perspective (your left or my left?). Consequently, representations of spatial term semantics must accommodate geometric, functional and pragmatics aspects of situated meaning.


## Problem description

### Interactive tasks

  - T1. Learning of spatial relations between objects on a table in interaction with humans in a real or virtual environment where the system also takes into account non-geometric features: dialogue for frame of reference negotiation and properties of objects.
  - T2. Interactively teach the system how to "put the mug on the table" and "put the mug on the shelf"? Notice that in both cases the final location of the mug is highly dependent on the type of the object involved.
  - T3. Generating route descriptions in a complex building in connection with navigation. How to generate route descriptions that provide the right kind of information so that a person finds the objects or location referred to?

These tasks can be explored in a real-life scenario with [our system based on the Kinect sensor](https://aclanthology.org/W17-0219/), a virtual environment/robot [Habitat AI](https://aihabitat.org) or, if you feel adventurous, the Unity game engine.


### Corpus-based tasks

  - T4. Extension of our earlier work which aims to identify automatically from corpus of textual image descriptions sensitivity of spatial relations to different kinds of knowledge: geometric (where) or functional (what). Can similar prediction be made from (visual) image data?
  - T5. How are spatial relations learned by vision and language neural models in image captions?
  - T6. Computational modelling of spatial perspective taking and the extension of the Cups dataset.

These tasks can be explored on vision and language corpora such as image captions and visual dialogue.


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
