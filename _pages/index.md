---
permalink: /
title: "Home"
news: true  # includes a list of news items
---


![](/assets/images/wordCloud.jpeg)

**UPDATE**: I will be graduating soon and am actively exploring research-focused opportunities in academia and industry. Please feel free to reach out if my background aligns with your team. I'm quick to pick up new concepts and enjoy working on complex, interdisciplinary problems.

I am a Ph.D. candidate in the Computational Science, Engineering, and Mathematics (CSEM) program at [The Oden Institute for Computational Engineering and Sciences](https://oden.utexas.edu/), The University of Texas at Austin. I am advised by [Dr. Patrick Heimbach](https://heimbach.wordpress.com/) in the [CRIOS research group](https://crios-ut.github.io/).

My research spans PDE-constrained Bayesian inverse problems, robust uncertainty quantification (UQ), physics-informed machine learning, and eXplainable AI (XAI). I develop methods to infer uncertain boundary conditions, initial states, and model parameters in a continental-scale ice sheet system (specifically, Greenland), using radiostratigraphy-derived age layer data. The goal is to improve the physical realism of ice sheet models and refine projections of sea level rise over the coming century.

I am deeply committed to open-source scientific software and have led several initiatives:
- Lead developer of [**SICOPOLIS-AD v2**](https://github.com/sicopolis/sicopolis/tree/ad), an adjoint-enabled ice sheet model for data assimilation
- Core contributor to [**MITgcm-AD v2**](https://github.com/MITgcm/MITgcm), a free and open-source alternative to the proprietary MITgcm adjoint
- Developer of Julia-based tools interfacing [Enzyme](https://enzyme.mit.edu) and MPI for glaciological modeling
- Reviewer for the *Journal of Open Source Software*

In Summer 2024, I interned at **Ansys** as a machine learning intern. I worked on a Generative AI pipeline that transforms a single user-provided image into a 3D object mesh for simulation workflows. The system combined amortized neural radiance fields (NeRFs) with 3D-aware diffusion models into a fast, scalable, and parallelizable framework.

Previously, I earned a B.Tech in Mechanical Engineering (with Honors) and a Minor in Computer Science from **IIT Bombay**, and an M.S. in Computational Science from **UT Austin**.

I’ve collaborated with researchers at Argonne National Lab, Scripps Institution of Oceanography, Hokkaido University, MIT, INRIA (France), IIT Bombay, and IIT Kanpur.

Outside of work, I enjoy tennis, yoga, reading, chess, cricket, and hiking. I also love spending time with our family dog, [Baloo](https://www.instagram.com/baloo.theterrier/).

## News
  {% for post in site.posts limit:5 %}
  <article>
    <b><time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time></b>
    <br>
    {{ post.content | markdownify | truncatewords: 500 }}
  </article>
  
{% endfor %}
