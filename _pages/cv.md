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
* BSc in Combined Major in Computer Science and Statistics, University of British Columbia, Vancouver, May 2022
* 

Work experience/ Research experience
======
* August 2022 –Present: Graduate Research Assistant at UBCCS
  * University of British Columbia, CS
  * Supervisor: [Profoessor Mijung Park](https://scholar.google.com/citations?hl=en&inst=17001591832933267808&user=fqKsAJcAAAAJ) and [Professor Xiaoxiao Li](https://xxlya.github.io/xiaoxiao/)
  * Currently working on Differentially Private Image Generation methods (See Publications)

*  May – August 2022 Research Assistant
  * University of British Columbia, CS
  * Supervisor: [Profoessor Mijung Park](https://scholar.google.com/citations?hl=en&inst=17001591832933267808&user=fqKsAJcAAAAJ) and [Professor Xiaoxiao Li](https://xxlya.github.io/xiaoxiao/)
  * We aim to provide trustworthy machine learning methods.

* May 2021 - August 2022: Research Assistant
  * University of British Columbia
  * Duties included: Develop ‘GaSP’ 2.0.0. 
  * Supervisor: [Professor William J. Welch, Department of Statistics](https://www.stat.ubc.ca/~will/)
    *	Worked with Professor William J. Welch, and Senior Data Scientist Hao Chen to develop Bayesian methods for GaSP 2.0.0, who first published their Bayesian Gaussian Process method on SIAM/ASA Journal.
    * The Bayesian methods proposed show some distinct advantages in terms of prediction accuracy and uncertainty quantification and will allow GaSP to be even more flexible. 

* April - August 2020 : Research Assistant
  * University of British Columbia
  * Developed ‘GaSP’, an R package with C code. See more in Publications.
  * Supervisor: [Professor William J. Welch, Department of Statistics](https://www.stat.ubc.ca/~will/)
    * Developed ‘GaSP’, an R package with C code. GaSP uses Gaussian processes and is used for analysis of computer experiments. GaSP uses available runs to fit a GP via MLE or MAP and predicts a result given untried parameters. It also has the capabilities to plot important effect plots, which makes GaSP much more useful and informative. Unlike other packages that implement GP models, GaSP is extremely robust and efficient. It has no issues with the scaling of training data and is suitable for handling large datasets.
    *	GaSP is now available on CRAN. See 'Publications' section.

  
Skills
======
* Machine learning: Differential Privacy, Reinforcement learning, Deep Learning, Convex optimization, Variational Inference, MDP, Bayesian Networks
* Statistics: Statistical Analysis, Statistical Learning, Sample Surveying, Missing values Imputation
* Computer Science: Operating Systems, Analysis of algorithms, Software Engineering, Graph theory
* Programming: C/C++, R, Python, PyTorch, JAX, Julia, Java, TypeScript, RcppArmadillo, Keras, Node.js

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
  {% endfor %}</ul>
  
Awards
======
* May 2023: UBC CS Graduate Teaching Assistant Award
* 2022S: UBC Work Learn International Undergraduate Research Award 
* 2020S: UBC Work Learn International Undergraduate Research Award 
* 2019W: Trek Excellence Scholarship (International Students)
