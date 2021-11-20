---
title: "Projects"
permalink: /projects/
layout: splash
entries_layout: grid
author_profile: true

feature_row:
  - image_path: assets/images/greenlandRadar.jpeg
    image_caption: "Image courtesy of CReSIS"
    alt: "GrIS Inverse Problem"
    title: "Bayesian Inverse Methods for Ice Sheet Model Calibration and Reconstruction"
    excerpt: "Calibrating ice sheet model SICOPOLIS using age layer radar data in order to project accurately into the future."
    url: /
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row_1:
  - image_path: /assets/images/mitgcmFKB.jpeg
    image_caption: "Image courtesy of [An T. Nyugen](https://oden.utexas.edu/people/1464/)"
    alt: "MITgcm with FKB"
    title: "Deep Learning Emulator for the dynamics of sea ice within the MITgcm model"
    excerpt: "Can we reduce the computational costs of dynamic sea ice models using Deep Learning?"
    url: /
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row_2:
  - image_path: assets/images/stampede2.jpeg
    image_caption: "Image courtesy of TACC"
    alt: "TNT course project"
    title: "Laplacian 2D Finite Difference (FD) solver on Stampede2 Supercomputer"
    excerpt: "Leveraged TACC's Stampede2 Supercomputer to build a heat equation solver."
    url: /
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row_3:
  - image_path: /assets/images/PINN.jpeg
    image_caption: "Image from L.Lu et. al (2019)"
    alt: "PINN"
    title: "Deep Mountain Glaciers"
    excerpt: "Leveraging Deep Learning to emulate as well as invert non-linear, highly diffusive mountain glacier model."
    url: /
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row_4:
  - image_path: assets/images/inverseProblem.jpeg
    image_caption: "Image from Isaac et. al (2015)"
    alt: "Inverse Problems Course"
    title: "Solving PDE-constrained inverse problems using FENICS"
    excerpt: "Solved ill-conditioned inverse problems using the adjoint equations and special second order methods."
    url: /
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row_5:
  - image_path: /assets/images/MLgeophysics.jpeg
    image_caption: "Data courtesy of Dr. Zoltan Sylvester"
    alt: "ML applications in geophysics"
    title: "Machine/Deep Learning applications in geophysics"
    excerpt: "Explored utility of autoencoders, GANs, CNNs, ML algorithms across multiple applications in geophysics."
    url: /
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row %}
{% include feature_row id="feature_row_1" type="left" %}
{% include feature_row id="feature_row_2" type="right" %}
{% include feature_row id="feature_row_3" type="left" %}
{% include feature_row id="feature_row_4" type="right" %}
{% include feature_row id="feature_row_5" type="left" %}

