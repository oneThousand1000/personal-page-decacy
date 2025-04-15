---
permalink: /
title: "About Me"
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Yiqian Wu (吴奕谦), now serving as an academic guest at [ETH Zurich](https://ethz.ch/en.html) (May 2024 - May 2025), working with Prof. [Siyu Tang](https://vlg.inf.ethz.ch/team/Prof-Dr-Siyu-Tang.html). Concurrently, I am a CS Ph.D. candidate (since 2021) at the [State Key Lab of CAD&CG](http://www.cad.zju.edu.cn), Zhejiang University, under the supervision of Prof. [Xiaogang Jin](http://www.cad.zju.edu.cn/home/jin). Prior to this, I accomplished my Bachelor's degree in Computer Science and Technology, graduating from the Chu Kochen College at Zhejiang University in 2021.

**Address:** Mengminwei Bldg, Zijingang Campus of Zhejiang University, 866 Yuhangtang Rd, Hangzhou 310058, China.

**ORCID:** [0000-0002-2432-809X](https://orcid.org/0000-0002-2432-809X)

**Contact:**  onethousand1250 [at] gmail.com 



I love painting!  I have posted some of my paintings on my [website](https://onethousandwu.com/artgallery/), and also shared some videos on [Bilibili](https://space.bilibili.com/6414209). I hope you will enjoy them too :)


## My Journey: Advancing 2D to 3D Avatar Generation

My current research focuses on portrait editing and generation. I have proposed two portrait image editing methods based on 2D GAN models, developed a dataset and designed a new architecture for 3D-aware face GANs. Currently, I am utilizing diffusion models for text-guided 3D avatar generation and extending this approach to enable animatability.

Below is an overview that showcases all of my papers through a single identity!

<img src="https://oneThousand1000.github.io/images/overview.png" width="100%" height="auto">


## Publications

**Explore the complete list of publications 👉️ [here](https://onethousandwu.com/publications/) .**

{% for post in site.publications reversed %}
  {% if post.year == '2025' and post.first_author == 'yes' %}
      {% include archive-abstract.html %}
  {% endif %}
{% endfor %}

{% for post in site.publications reversed %}
  {% if post.year == '2024' and post.first_author == 'yes' %}
      {% include archive-abstract.html %}
  {% endif %}
{% endfor %}

{% for post in site.publications reversed %}
  {% if post.year == '2023' and post.first_author == 'yes' %}
      {% include archive-abstract.html %}
  {% endif %}
{% endfor %}

{% for post in site.publications reversed %}
  {% if post.year == '2022' and post.first_author == 'yes' %}
      {% include archive-abstract.html %}
  {% endif %}
{% endfor %}

{% for post in site.publications reversed %}
  {% if post.year == '2021' and post.first_author == 'yes' %}
      {% include archive-abstract.html %}
  {% endif %}
{% endfor %}


## Experience

{% include experience.html %}