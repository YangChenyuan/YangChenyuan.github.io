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

I received my B.S. degree from the elite program in the Department of Computer Science & Technology at Nanjing University, advised by Prof. [Yanyan Jiang](https://cs.nju.edu.cn/ics/people/yanyanjiang/index.html). 

My research interest lies in the area of software engineering, especially in software testing. I have found 30+ bugs for [VSCode-Vim](https://github.com/VSCodeVim/Vim), lots of bugs for [PyTorch](https://github.com/pytorch/pytorch) and one very interesting bug for [NumPy](https://github.com/numpy/numpy).


## Publications

{% for post in site.publications reversed %}
  {% include archive-paper.html %}
{% endfor %}