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
======
* Ph.D in Computer Science, MIT, 2015-2020 Sep. 
* B.S. in Precision Instruments & Computer Science, Tsinghua University, 2011-2015

Work experience
======
* 03/2024-Now: Senior Research Scientist at Meta GenAI
  * Working on improving LLAMA-3 model on model reasoning and instruction following via SFT and RLHF

* 09/2020-02/2024: Senior Applied Scientist at Amazon AGI
  * Served as a tech lead on the ChatGPT-like Large Language Model project (Amazon Olympus Model) for model reasoning workstream
  * Devised new methods to align LLMs with human feedback, such as reward based data augmentation, constitutional critique and revision, RLAIF, self-alignment, etc.
  * Published a SOTA method for knowledge grounded response generation with web-search based question answering
  * Published SOTA models for enabling bots to address out-of-API user queries with external unstructured knowledge sources
  * Published a SOTA utterance rewriting model to resolve co-references and ellipsis to help bots better understand dialogue context
  * Launched better models for detecting and reducing contradiction and factual inconsistency in bots' responses
  * Published new datasets and models for selecting better responses out of many candidates for open-domain chit-chatting 
  
Skills
======
* Natual Language Processing
* Large Language Model
  * Model Alignment with Human/AI feedback
  * Model Reasoning, e.g. math and coding
  * Model Evaluation
  * LLM for Agents
* Multi-modal LLM

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
