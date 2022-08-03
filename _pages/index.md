---
permalink: /
title: "Home"
news: true  # includes a list of news items
---


![](/assets/images/wordCloud.jpeg)

I am a fourth year Ph.D. student at the [Oden Institute for Computational Engineering and Sciences](https://oden.utexas.edu/) at The University of Texas at Austin. I am currently also serving as the Vice President of the [UT Student Chapter of SIAM](https://siam.oden.utexas.edu/). I am also serving as a teaching assistant for the course "Introduction to Mathematical Modeling in Science and Engineering". 

I am broadly interested in physics informed machine learning, optimization, inverse problems, uncertainty quantification, computational glaciology, and computational oceanography. I am currently involved in several research efforts with my advisor [Dr. Patrick Heimbach](https://heimbach.wordpress.com/) and our research group [CRIOS](https://crios-ut.github.io/), as well as several other collaborators ‐ 

1. Bayesian Inverse Methods for Greenland Ice Sheet Model Calibration and Reconstruction over long time scales 
2. Deep Learning Emulator for the dynamics of sea ice within the MITgcm model
3. Developing open-source adjoint code for the MITgcm ocean model (as part of my visit to Argonne National Laboratory)

Over the course of my work, I have collaborated with researchers from Argonne National Laboratory, Scripps Institution of Oceanography, Hokkaido University, IIT Kanpur, MIT, and Institut National de Recherche en Informatique et Automatique(INRIA), France.

I am passionate about Open Source Software Development, and have contributed substantially to efforts such as SICOPOLIS-AD v2, MITgcm, and ARGOVIS. I have also developed Julia codes which interface Enzyme and MPI for glacier models, and reported fundamental bugs within Enzyme.

Previously, I completed B.Tech in Mechanical Engineering (with Honors) and Minor in Computer Science from the Indian Institute of Technology, Bombay (IIT-Bombay), Mumbai, India in May 2019. I also received my Masters Degree in Computational Science, Engineering and Mathematics from UT Austin in May 2021. 

In my free time, I like hiking, playing chess, cricket, and reading (mostly history and fiction). I have also recently taken up cubing, and can solve up to a 5x5. All of these activities are a lot more fun when [Baloo](https://www.instagram.com/babybaloo.thelab/) is also involved.

## News
  {% for post in site.posts limit:5 %}
  <article>
    <b><time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time></b>
    <br>
    {{ post.content | markdownify | truncatewords: 500 }}
  </article>
  
{% endfor %}
