---
title: "Welcome to my website"
layout: single
excerpt: "About me"
author_profile: true
permalink: /
redirect_from: 
  - /about/
  - /about.html
---

I am a Ramanujan Faculty Fellow in the [Department of Mechanical Engineering](https://iitpkd.ac.in/mechanical-engineering),[Indian Institute of Technology, Palakkad](https://iitpkd.ac.in/). My research lies at the intersection of computational science and engineering, encompassing a broad range of topics such as high-accuracy numerical scheme development, high-performance scientific computing, and scientific machine learning. My work is driven by a passion for exploring innovative approaches to solving complex problems in engineering and the applied sciences.




{% include base_path %}
## Selected publications
{% for post in site.selectedpub reversed %}
{% if post.type == 'journal' %}
{% include archive-single-journal-short.html %}
{% endif %}
{% endfor %}
