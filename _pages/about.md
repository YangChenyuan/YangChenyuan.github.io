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

My research aims to improve the *reliability* of software systems.
I am interested in leveraging testing, analysis, and verification techniques to make software systems more *reliable* and *robust*, especially for machine learning systems.
Besides, I tremendously enjoy contributing to the open-source community.

Currently, I focus on testing deep learning compilers and the Linux kernel. Until now, my work has totally detected **353** previously unknown bugs for widely-used deep learning systems, including [PyTorch](https://pytorch.org), [TensorFlow](https://www.tensorflow.org), [JAX](https://jax.readthedocs.io) and [OneFlow](https://github.com/Oneflow-Inc/oneflow), and **8 CVEs** for the Linux kernel.

Besides deep learning systems and the Linux kernel, I also reported more than **30** bugs for other open-source projects, such as [NumPy](https://numpy.org), [Moby](https://mobyproject.org), and [VSCode-Vim](https://github.com/VSCodeVim/Vim).


## Publications

{% for post in site.publications reversed %}
  {% include archive-paper.html %}
{% endfor %}

<i>* denotes  joint first authors</i>

## Internships

**Microsoft Research**, [Systems Research Group](https://www.microsoft.com/en-us/research/group/systems-research-group-redmond/overview/) <i style="float:right;text-align:right;">Summmer 2024 (TBD)</i>
**Google Labs**, [Project Starline](https://blog.google/technology/research/project-starline-prototype/) <i style="float:right;text-align:right;">Summmer 2023</i>

## Talks

Fuzzing Deep-Learning Libraries via Automated Relational API Inference

  - Software Engineering Retreat, University of Illinois at Urbana-Champaign, Sept. 2022

Free Lunch for Testing: Fuzzing Deep-Learning Libraries from Open Source

  - [iSE symposium](http://www.iselab.cn/ises2022/), Nanjing University, May 2022