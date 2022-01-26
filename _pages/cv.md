---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* BSc in Combined Major in Computer Science and Statistics, University of British Columbia, Vancouver, April 2022 (expected)

Work experience/ Research experience
======

* May 2021 - Present: Research Assistant
  * University of British Columbia
  * Duties included: Develop ‘GaSP’ 2.0.0. 
  * Supervisor: [Professor William J. Welch, Department of Statistics](https://www.stat.ubc.ca/~will/)
    *	Currently working with Professor William J. Welch, and Senior Data Scientist Hao Chen to develop Bayesian methods for GaSP 2.0.0, who first published their Bayesian Gaussian Process method on SIAM/ASA Journal.
    * The Bayesian methods proposed show some distinct advantages in terms of prediction accuracy and uncertainty quantification and will allow GaSP to be even more flexible. 

* April - August 2020 : Research Assistant
  * University of British Columbia
  * Developed ‘GaSP’, an R package with C code. See more in Publications.
  * Supervisor: [Professor William J. Welch, Department of Statistics](https://www.stat.ubc.ca/~will/)
    * Developed ‘GaSP’, an R package with C code. GaSP uses Gaussian processes and is used for analysis of computer experiments. GaSP uses available runs to fit a GP via MLE or MAP and predicts a result given untried parameters. It also has the capabilities to plot important effect plots, which makes GaSP much more useful and informative. Unlike other packages that implement GP models, GaSP is extremely robust and efficient. It has no issues with the scaling of training data and is suitable for handling large datasets.
    *	GaSP is now available on CRAN. See 'Publications' section.

  
Skills
======
* Machine learning: Deep Learning, MCMC, Descent Methods, Clustering, Variational Inference, convex optimization
* Statistics: Statistical Analysis, Statistical Learning, Sample Surveying, MLE, MAP, Missing values Imputation
* AI: Reinforcement learning, MDP, Bayesian Networks, Clustering, Decoding
* Computer Science: Operating Systems, Analysis of algorithms, Software Engineering, Graph theory
* Programming: C/C++, R, Python, Julia, Java, TypeScript, RcppArmadillo, Keras, Node.js

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Projects
======
  <ul>{% for post in site.projects %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  
Awards
======
* 2020S: UBC Work Learn International Undergraduate Research Award 
* 2019W: Trek Excellence Scholarship (International Students)
