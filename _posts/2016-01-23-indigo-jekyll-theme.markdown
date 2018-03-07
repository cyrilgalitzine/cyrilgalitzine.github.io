---
title: "Inference of stochastic organelle dynamics"
layout: post
date: 2018-02-01 22:01
tag: Inference
image: https://koppl.in/indigo/assets/images/jekyll-logo-light-solid.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "This is a simple and minimalist template for Jekyll for those who likes to eat noodles."
category: project
author: cg
externalLink: false
---
The regulation of organelle abundance sustains critical biological processes, such as metabolism and energy production. Biochemical models mathematically express these temporal changes in terms of reactions, and their rates. The rate parameters are critical components of the models, and must be experimentally inferred. However, the existing methods for rate inference are limited, and not directly applicable to organelle dynamics.
We introduced a novel approach that integrates modeling, inference and experimentation, and incorporates biological replicates, to accurately infer the rates. The approach relies on a biochemical model in form of a stochastic differential equation, and on a parallel implementation of inference with particle filter. It also relies on a novel microscopy workflow that monitors organelles over long periods of time in cell culture. Evaluations on simulated datasets demonstrated the advantages of this approach in terms of increased accuracy and shortened computation time. An application to imaging of peroxisomes (a type of organelle) determined that fission, rather than de novo generation, is predominant in maintaining the organelle level under basal conditions. This biological insight serves as a starting point for a system view of organelle regulation in cells.

This work will be presented at the [2018 RECOMB conference ](https://recomb2018.fr/) and published in the conference proceedings. 
You can find a preprint of this paper [here](https://recomb2018.fr/).
---


