---
permalink: /
title: "Home"
news: true  # includes a list of news items
---


![](/assets/images/wordCloud.jpeg)

I am a Ph.D. candidate in the Computational Science, Mathematics, and Engineering (CSEM) program at [The Oden Institute for Computational Engineering and Sciences](https://oden.utexas.edu/) at The University of Texas (UT) at Austin. I am advised by [Dr. Patrick Heimbach](https://heimbach.wordpress.com/) as part of the research group [CRIOS](https://crios-ut.github.io/). I am broadly interested in data assimilation under uncertainty, machine learning, optimization, and mathematical modeling of systems.

My research primarily involves PDE-constrained inverse problems in the context of paleoclimate reconstruction over ice sheets. We are trying to leverage the recently collected radiostratigraphy-based age layer data to constrain the paleoclimate of the ice sheet during the last 11,000 years. We hypothesize that a better-constrained ice sheet model can better forecast sea level rise contributions in the next century.

I have also been exploring the utility of Explainable AI (XAI) methods such as Layerwise Relevance Propagation (LRP) and how they compare to adjoint gradients in an oceanic and glaciological context. Adjoint gradients can be a useful sanity check for XAI methods, helping gauge if the neural networks can accurately capture the underlying physics.

I am a reviewer at the Journal of Open Source Software (JOSS) and the Journal of Mountain Science (JMS). I am passionate about Open Source Software Development and have contributed substantially to efforts to make open-source adjoint models available for data assimilation efforts of the glaciology and oceanography communities by leveraging open-source Automatic Differentiation (AD) tools. I am the lead developer and maintainer of the ice-sheet model adjoint SICOPOLIS-AD v2. We have developed an open-source adjoint for the ocean general circulation model, MITgcm-AD, which offers an alternative to a proprietary version that costs ~$14,000 per year per individual license. I have also developed Julia codes which interface Enzyme and MPI for glacier models and reported fundamental bugs within Enzyme.

Over the course of my work, I have collaborated with researchers from Indian Institute of Technology (IIT) Bombay, UT Austin, Argonne National Laboratory, Scripps Institution of Oceanography, Hokkaido University, IIT Kanpur, MIT, and Institut National de Recherche en Informatique et Automatique(INRIA), France.

In Summer 2024, I was a machine learning intern at Ansys. I got to work on a really cool project that leverages Generative-AI (GenAI) to help users auto-generate geometries and meshes for downstream numerical simulation tasks. Given a single image of any object by the user, the machine learning model generated a reasonable 3D object geometry representation as a neural field, from which a mesh can be recovered. This project leveraged amortized neural radiance fields (NeRFs) and the latest 3D-aware diffusion models together in a unified framework that is fast, parallelizable, and scalable.

Previously, I completed a B.Tech in Mechanical Engineering (with Honors) and a Minor in Computer Science from the IIT Bombay, Mumbai, India in May 2019. I received my Master's in Computational Science, Engineering, and Mathematics from UT-Austin in May 2021.

In my free time, I like hiking, playing chess, cricket, and reading (mostly history and fiction). I have also recently taken up cubing, and can solve up to a 5x5. All of these activities are a lot more fun when [Baloo](https://www.instagram.com/baloo.theterrier/) is also involved.

## News
  {% for post in site.posts limit:5 %}
  <article>
    <b><time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time></b>
    <br>
    {{ post.content | markdownify | truncatewords: 500 }}
  </article>
  
{% endfor %}
