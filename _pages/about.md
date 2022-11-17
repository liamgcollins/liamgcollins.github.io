---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**About Me**

I am a fourth-year PhD student at the University of Texas at Austin co-advised by [Aryan Mokhtari](https://sites.utexas.edu/mokhtari/) and [Sanjay Shakkottai](https://sites.google.com/view/sanjay-shakkottai/home). I am interested in the theoretical foundations of multi-task learning, particularly in federated learning and meta-learning contexts. Before UT, I did my undergraduate at Princeton University, where I worked with [Yuxin Chen](https://yuxinchen2020.github.io/). 

My CV can be found here (updated 11/2022).

## Recent News

- In October 2022 I gave a [talk](https://sites.google.com/view/one-world-seminar-series-flow/archive/2022) on representation learning in federated learning at the Federated Learning One World (FLOW) Seminar.

- I interned at Amazon Alexa in summer 2022 under the supervision of [Jie Ding](https://jding.org/) and [Tanya Roosta](https://www.amazon.science/author/tanya-g-roosta). My project studied personalized federated learning with side information.


## Publications

{% if author.googlescholar %}
  My articles can also be found on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<!---{% for post in site.publications reversed %}
          {% include archive-single.html %}
     {% endfor %}--->

**FedAvg with Fine-Tuning: Local Updates Lead to Representation Learning**  
*LC, Hamed Hassani, Aryan Mokhtari, Sanjay Shakkottai*  
NeurIPS 2022     
[\[PDF\]](https://arxiv.org/pdf/2205.13692.pdf)

**MAML and ANIL Provably Learn Representations**  
*LC, Aryan Mokhtari, Sewoong Oh, Sanjay Shakkottai*  
ICML 2022     
[\[PDF\]](https://arxiv.org/pdf/2202.03483.pdf)

**How does the Task Landscape Affect MAML Performance?**  
*LC, Aryan Mokhtari, Sanjay Shakkottai*  
CoLLAs 2022 *Oral Presentation*   
[\[PDF\]](https://arxiv.org/pdf/2010.14672.pdf)

**Exploiting Shared Representations for Personalized Federated
Learning**  
*LC, Hamed Hassani, Aryan Mokhtari, Sanjay Shakkottai*  
ICML 2021    
[\[PDF\]](https://arxiv.org/pdf/2102.07078.pdf) [\[Code\]](https://github.com/lgcollins/FedRep)

**Task-Robust Model-Agnostic Meta-Learning**  
*LC, Aryan Mokhtari, Sanjay Shakkottai*  
NeurIPS 2020    
[\[PDF\]](https://arxiv.org/abs/2002.04766.pdf) [\[Code\]](https://github.com/lgcollins/tr-maml)
