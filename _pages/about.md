---
permalink: /
title: "Chenyuan Yang"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## About

I am **Chenyuan Yang** (杨晨源), a PhD student at [UIUC](https://illinois.edu/) advised by Prof. [Lingming Zhang](http://lingming.cs.illinois.edu/) since 2022 Fall.

I received my B.S. degree with honors from the elite program in the Department of Computer Science & Technology at [Nanjing University](https://www.nju.edu.cn/EN/main.htm), advised by Prof. [Yanyan Jiang](https://cs.nju.edu.cn/ics/people/yanyanjiang/index.html). 

My research aims to improve the reliability of the software system. I focus on leveraging different testing techniques to make the software system more reliable and robust, especially for machine learning systems.
Besides, I am also interested in making the testing framework more effective and efficient.

I have found lots of bugs for [PyTorch](https://pytorch.org) and [TensorFlow](https://www.tensorflow.org). Besides, I also found more than 30 bugs for [VSCode-Vim](https://github.com/VSCodeVim/Vim), one bug for [Moby](https://mobyproject.org) and one very interesting bug for [NumPy](https://numpy.org).


## Publications

{% for post in site.publications reversed %}
  {% include archive-paper.html %}
{% endfor %}