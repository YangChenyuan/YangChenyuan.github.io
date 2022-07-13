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

I am **Chenyuan Yang** (杨晨源), a senior undergraduate from the elite program in the Department of Computer Science & Technology at Nanjing University. I am an incoming CS PhD student at UIUC this fall, advised by Prof. Lingming Zhang.

My research interest lies in the area of software engineering, especially in software testing. I have found 30+ bugs for [VSCode-Vim](https://github.com/VSCodeVim/Vim), lots of bugs for [PyTorch](https://github.com/pytorch/pytorch) and one very interesting bug for [NumPy](https://github.com/numpy/numpy).


## Publications

{% for post in site.publications reversed %}
  {% include archive-paper.html %}
{% endfor %}