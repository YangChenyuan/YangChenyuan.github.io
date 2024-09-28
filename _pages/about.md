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

My research focuses on enhancing the *reliability* of software systems, such as machine learning models, compilers, and operating system kernels. To achieve this, I employ a combination of *testing*, *analysis*, and *verification* techniques, with a particular emphasis on leveraging the power of *large language models* (LLMs).

To date, my work has uncovered over **400** previously unknown bugs in widely-used machine learning systems, including [PyTorch](https://pytorch.org), [TensorFlow](https://www.tensorflow.org), [JAX](https://jax.readthedocs.io), as well as 9 CVEs for the Linux kernel.

Besides deep learning systems and the Linux kernel, I also reported more than **30** bugs for other open-source projects, such as [NumPy](https://numpy.org), [Moby](https://mobyproject.org), and [VSCode-Vim](https://github.com/VSCodeVim/Vim).


## Publications

{% for post in site.publications reversed %}
  {% include archive-paper.html %}
{% endfor %}

<i>* denotes  joint first authors</i>

## Internships

**Microsoft Research**, [Systems Research Group](https://www.microsoft.com/en-us/research/group/systems-research-group-redmond/overview/) <i style="float:right;text-align:right;">Summmer 2024</i>

**Google Labs**, [Project Starline](https://blog.google/technology/research/project-starline-prototype/) <i style="float:right;text-align:right;">Summmer 2023</i>

## Talks

Fuzzing Deep-Learning Libraries via Automated Relational API Inference

  - Software Engineering Retreat, University of Illinois at Urbana-Champaign, Sept. 2022

Free Lunch for Testing: Fuzzing Deep-Learning Libraries from Open Source

  - [iSE symposium](http://www.iselab.cn/ises2022/), Nanjing University, May 2022