---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## About

I am **Chenyuan Yang** (杨晨源), a PhD student at [UIUC](https://illinois.edu/) advised by Prof. [Lingming Zhang](http://lingming.cs.illinois.edu/) since 2022 Fall.

I received my B.S. degree with honors from the elite program in the Department of Computer Science & Technology at [Nanjing University](https://www.nju.edu.cn/EN/main.htm), advised by Prof. [Yanyan Jiang](https://ics.nju.edu.cn/~jyy/). 

My research covers the interaction of software systems and machine learning, with the goal of enhancing the reliability of large-scale systems.
To this end, I leverage and optimize LLMs with testing, reasoning, and verification techniques.
To date, my research has detected **630+ critical** bugs for *ML systems, C/C++ compilers, and operating systems*, including **25 CVEs**.

- **System Reliability for ML**. Synthesizing diverse & high-quality tensor programs across inference, training, and optimization components in ML systems, along with test oracles.
- **ML for System Reliability**.
  - **LLM for Testing**. Designing LLM-driven workflows to synthesize tests, test generators, and static analyzers for large-scale software systems. Evaluating LLMs’ code reasoning via test generation.
  - **LLM for Verification**. Training and evaluating LLMs to generate verification proofs for code.

## Selected Publications

For a full list of publications, please refer to [Publications](/publications/).

{% for post in site.publications reversed %}
  {% if post.selected %}
    {% include archive-paper.html %}
  {% endif %}
{% endfor %}

<i>* denotes  joint first authors</i>

## Internships

**Microsoft Research**, [Systems Research Group](https://www.microsoft.com/en-us/research/group/systems-research-group-redmond/overview/) <i style="float:right;text-align:right;">Summmer 2024</i>

**Google Labs**, [Project Starline](https://blog.google/technology/research/project-starline-prototype/) <i style="float:right;text-align:right;">Summmer 2023</i>
