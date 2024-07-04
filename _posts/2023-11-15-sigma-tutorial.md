---
layout: post
title: SIGMA tutorial&#58; python code to analyse hyper-spectral imaging datasets
date: 2023-11-15
description: A jupyter-notebook tutorial using GUIs to analyse energy dispersive X-ray spectroscopy (EDX) datasets.

tags: jupyter tutorial
categories: sigma
giscus_comments: false
related_posts: false
# featured: true
---

This tutorial is a demo of SIGMA analysis on an SEM-EDX dataset. Please check the [github page](https://github.com/poyentung/sigma) for installation and details.

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/sigma_tutorial.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/sigma_tutorial.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
{% jupyter_notebook jupyter_path %}
{% else %}

<p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}