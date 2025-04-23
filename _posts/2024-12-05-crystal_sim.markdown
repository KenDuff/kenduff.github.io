---
layout: post
title: "Crystalization Simulation Project"
date:   2024-12-05 22:30:27
categories: Undergraduate Projects
tags: featured
image: "/assets/article_images/crystal_sim/cover.png"
---
This project was designed at the University of Saskatchewan for the course CMPT 394: Simulation Principles.

The motivation for the project was to visualize the properties and distribution of crystals, given conditions in which a crystalline structure would be present. We define these crystals as having two properties. The first would be an overall 'size', which we define as φ, and an 'order', defined as n. We want to analyze these values of φ and n up to a pre-specified value of N.

We do this by viewing the change in concentrations based on four coefficients we title as Crystal Growth, Decay, Order, and Disorder. To calculate these changes, we structured the model as a series of differential equations, which, when we perform summation on, would yield our overall system, and the total change we would see in that specific size and order of crystal.

The goal of the model was to gain an understanding of the concentration of sub-crystal amounts for the values of $\phi$ and $n$ that the system can take on. From this, we can characterize the conditions of the system and what effect it would have on the formation of these crystals, enabling us to understand the most ideal crystal given specific external characteristics represented by the coefficients of the system.

You can read my full report about this interesting topic here ([View Report](https://kenduff.github.io/assets/article_reports/crystal_sim/crystalSimulationReport.pdf))



[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
