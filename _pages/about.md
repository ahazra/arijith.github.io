---
permalink: /
[//]: # title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
title: "Welcome to my website"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my website.
Currently, I am Ramanujan Faculty Fellow at the [Department of Mechanical Engineering](https://iitpkd.ac.in/mechanical-engineering),[Indian Institute of Technology, Palakkad](https://iitpkd.ac.in/)
With a basic background in mechanical engineering, I conducted my research in different aspects of computational science, 
starting from code development, high-performance scientific computing, devising numerical schemes as well as the cutting-edge paradigm of 
scientific machine learning and deep learning.


Research interest
======

My research interest lies broadly in areas of i) Computational methods for partial differential
equations especially electrodynamics, magnetohydrodynamics. ii) Application of machine
and deep learning in engineering and sciences. Currently, I am engaged in the following research projects:

**Computational electrodynamics**
I develop discontinuous Galerkin-based higher order numerical methods for computational electrodynamics 

**Deep learning based inversion**

**PhD work** During my PhD, I was working in an interdisciplinary group of scientists dedicated to work in MRI. I was the lone wolf in that group working in the numerical modelling and simulation of flow MRI. Though, I never performed any research in the field of image reconstruction, digital signal processing, algebraic image reconstruction (which is basically an inverse problem, from time to time I go back to these topics and 

Academic background
======


{% include base_path %}
# Selected publications
{% for post in site.publications reversed %}
{% if post.type == 'selected' %}
{% include archive-single-cv.html %}
{% endif %}
{% endfor %}
