---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## 2022

{% capture written_year %}'2022'{% endcapture %}

{% for post in site.publications reversed %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year == written_year %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

## 2021

{% capture written_year %}'2021'{% endcapture %}

{% for post in site.publications reversed %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year == written_year %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

## 2020

{% capture written_year %}'2020'{% endcapture %}

{% for post in site.publications reversed %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year == written_year %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
