---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
=========

* **Hong Kong University of Science and Technology (HKUST)**, Hong Kong
  B.Eng. in Computer Engineering, expected graduation 2028
  * Cumulative Grade Average: 4.141/4.3 (Top 1%)

Research Experience
===================

* **AutoTour: Automatic Photo Tour Guide with Smartphones and LLMs**
  * Research project on smartphone-based tour guidance systems using large language models.
  * Preprint available at [arXiv:2601.06781](https://arxiv.org/abs/2601.06781).

* **MMRouter**
  * Research project on routing multimodal queries to improve cost-performance trade-offs in model selection.

Selected Projects
=================

* **Nuola (挪啦): Critical SMS Detection and Alert Mobile App**
  * Flutter application for critical SMS detection and real-time alerting, with emphasis on dependable mobile deployment.
  * Deployed on major Android app galleries in China; recorded over 500 active users in the first month and generated initial revenue.

* **VocabuStory**
  * LLM-powered Flutter application for language learning through customized narrative generation and interactive content design.

* **Agent Skills for Study Automation**
  * Designed and authored two reusable agent skills, `summarize-slides` and `homework-solver`, built around multi-agent collaboration for study support workflows.
  * Shared the work publicly, receiving 6,000+ likes and saves on Xiaohongshu and 80+ GitHub stars.

Honors and Awards
=================

* SENG Dean's List, HKUST (Fall 2024; Spring 2025; Fall 2025)
* University's Scholarship Scheme for Continuing Undergraduate Students (HKD 40,000)

Technical Skills
================

* Programming: Python, C++, Dart, JavaScript
* Machine Learning: NumPy, Pandas, PyTorch, Matplotlib
* Development: Flutter, full-stack application development
* Systems: Linux

Relevant Coursework
===================

* COMP1021 Introduction to Python (A+)
* COMP2011 C++ Programming (A)
* COMP2012 Object-Oriented Programming and Data Structures (A)
* COMP2211 Exploring Artificial Intelligence with Python (A)

Publications
============

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
========

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service
========

* Co-founder and Coding Team Lead, HKUST-UGAIL
* Engineering Student Ambassador, HKUST
* Undergraduate Teaching Assistant, COMP1023, HKUST
