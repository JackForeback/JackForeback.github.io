---
layout: page
title: Attention In An ScVAE
description: Experimented with adding attention into the latent space of a VAE.
img: assets/img/project_imgs/gv.jpg
importance: 9
category: research
---

I started this project in the Summer of 2024. For a little background, I majored in electrical engineering my 
first semester, and transitioned into computer science my second semester. So at the time of this project I had 
about 6 months of coding experience and even less with AI. Thanks to the mentorship of Dr. Zachary DeBruine and team 
members like Jagger Denhof and Tony Boos, I was able to produce some nice experimental results over the summer.

I built and tested a custom attention module against the PyTorch implementation, and ran experiments 
adding the modules into the layers surrounding the latent space of our single cell variational autoencoder. 
I also built the first model with a successful UMAP, and later made the first implementation of a multimodal 
variational autoencoder, which had designated networks for human and mouse cells and attempted to cross 
generate between them, but that is not included in the paper which is only for the original summer project.

---

[**Paper (PDF)**](/assets/pdf/GVSU_paper.pdf) &nbsp;·&nbsp; [**Poster (PDF)**](/assets/pdf/GVSU_poster.pdf) &nbsp;·&nbsp; [**Code (GitHub)**](https://github.com/zdebruine/MMVAE)
