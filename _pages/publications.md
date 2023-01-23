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

{% for post in site.publications reversed %}
  {% if post.year == '2022' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

## 2021

{% for post in site.publications reversed %}
  {% if post.year == '2021' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

## 2020

{% for post in site.publications reversed %}
  {% if post.year == '2020' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
