---
permalink: /
title: "🙋🏻‍♂️ About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m a second-year Ph.D. student at VLISLab, Nagoya University, interested in high-level CV topics from detection to segmentation vision.

Prior to Nagoya University, I obtained my B.ENG and M.ENG in Information and Communication Engineering from Northeastern University (NEU), where I focused on medical image analysis.

Lately, I’ve been focusing on Open-Vocabulary Vision tasks.


News
======
  <ul>{% for post in site.news %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


Publications
======
  {% include_relative publications.md %}



Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Education
======
  <ul>{% for post in site.education %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Awards
======
  <ul>{% for post in site.award %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
