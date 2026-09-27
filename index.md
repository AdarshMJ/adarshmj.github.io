---
layout: page
title: About
order: 1
hide_title: true
image: /assets/profile.jpeg
social_image: /assets/adarsh.jamadandi.jpg
description: Adarsh Jamadandi is a CNRS doctoral researcher at IRISA studying graph diffusion models, memorization, generalization, and scalable graph generation.
---

<img src="{{ page.image }}" alt="Adarsh Jamadandi" class="profile-photo" width="160" height="213">

Hi 👋

I'm Adarsh Jamadandi, a CNRS doctoral researcher at IRISA, Rennes, working on
diffusion models for graphs with [Dr. Nicolas Keriven](https://nkeriven.github.io).
I study the learning dynamics of discrete diffusion models for graph generation —
when they generalize versus memorize — with the goal of building more efficient
models that scale to large graphs.

Previously I was a research assistant at [SprintML](https://sprintml.com/team/)
with Franziska Boenisch and Adam Dziedzic, where we built the first framework for
studying memorization in GNNs. 

I did my Master's at Saarland University, with a
thesis at the [Relational ML Lab](https://relationalml.github.io) under Rebekka
Burkholz on mitigating over-squashing and over-smoothing to improve GNN
generalization. 

I obtained my Bachelor's in Electronics and Communication Engineering from India, with a thesis on video
anomaly detection advised by
[Dr. Uma Mudenagudi](https://scholar.google.co.in/citations?user=xBaqwmkAAAAJ&hl=en).

<nav class="profile-links" aria-label="Research profiles and curriculum vitae">
  <a href="https://scholar.google.com/citations?user={{ site.google_scholar_username }}">Google Scholar</a>
  <a href="https://orcid.org/{{ site.orcid_id }}">ORCID</a>
  <a href="https://github.com/{{ site.github_username }}">GitHub</a>
  <a href="https://www.linkedin.com/in/{{ site.linkedin_username }}">LinkedIn</a>
  <a href="{{ '/assets/AdarshCVNew.pdf' | prepend: site.baseurl }}">CV</a>
</nav>

#### Selected Research

{% include selected-research.html %}

#### Updates

{% include updates.html %}
