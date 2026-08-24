---
layout: page
title: Attention ScVAE
description: Experimented with adding attention into the latent space of a VAE.
img: assets/img/placeholder.jpg
importance: 1
category: research
---

I started this project in the Summer of 2024. For a little background, I majored in electrical engineering my 
first semester, and transitioned to computer science my second semester. So at the time of this project I had 
about 6 months of experience coding. Thanks to the mentorship of Dr. Zachary DeBruine and team members like 
Jagger Denhof and Tony Boos, I was able to produce some nice experimental results over the summer.

I was able to build and test a custom attention module against the pytorch implementation, and run experiments 
adding the modules into the layers surrounding the latent space of our single cell variational autoencoder. 
I built the first model with a successful UMAP, and later made the first implementation of a multimodal 
variational autoencoder, which had designated networks for human and mouse cells and attempted to cross 
generate between them. After this I left the project to pursue more math inspired projects, leading to my 
REU at Brown.

---

[**Paper (PDF)**](/assets/pdf/GVSU_paper.pdf) &nbsp;·&nbsp; [**Code (GitHub)**](https://github.com/zdebruine/MMVAE)
