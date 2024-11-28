---
title: Data-Adaptive Dimensional Analysis for Accurate Interpolation and Extrapolation in Computer Experiments
summary: arXiv Preprint
tags:
- Machine Learning
- Data Analysis
- Statistics and Probability
- Applications
- Dimensional Analysis
date: "2023-12-14T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

links:
url_code: ""
url_pdf: "https://arxiv.org/abs/2312.10100"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Dimensional analysis (DA) pays attention to fundamental physical dimensions such as length and mass when modelling scientific and engineering systems. It goes back at least a century to Buckingham's Pi theorem, which characterizes a scientifically meaningful model in terms of a limited number of dimensionless variables. The methodology has only been exploited relatively recently by statisticians for design and analysis of experiments, however, and computer experiments in particular. The basic idea is to build models in terms of new dimensionless quantities derived from the original input and output variables. A scientifically valid formulation has the potential for improved prediction accuracy in principle, but the implementation of DA is far from straightforward. There can be a combinatorial number of possible models satisfying the conditions of the theory. Empirical approaches for finding effective derived variables will be described, and improvements in prediction accuracy will be demonstrated. As DA's dimensionless quantities for a statistical model typically compare the original variables rather than use their absolute magnitudes, DA is less dependent on the choice of experimental ranges in the training data. Hence, we are also able to illustrate sustained accuracy gains even when extrapolating substantially outside the training data.

This preprint is part of my PhD dissertation supervised by William J. Welch, Professor in the Deparment of Statistics at UBC.

