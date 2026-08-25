---
layout: page
title: REU On Bias In Classification
description: Identified class convergence gap and developed mitigation strategies.
img: assets/img/project_imgs/brown.jpg
importance: 8
category: research
---

I had a great summer REU experience at Brown. I met some amazing people, faculty, and friends. It only reinforced 
that I wanted to continue doing research as my career. After identifying the Max-Min class gap, I began using 
projection methods to attempt to mitigate it throughout training. Prior literature indicated that projecting data 
using spectral/manifold information meaningfully mitigates class bias, but I found that class bias can still emerge 
during training regardless. This illustrates the fact that a random initialization will inherently have bias.

This initialization effect could lessen as networks grow in size, but regularization techniques like early stopping can 
still inject model bias when there is a Max-Min class gap during training. The primary contribution was a position paper 
below introducing the Max-Min class gap. I later went back and introduced an alternating linear solver and evolving 
weights to try and mitigate bias from initialization and speed up learning by initializing weights from orthogonal basis 
functions. 

I feel that I left a lot on the table with this project, and wish I could go back and approach it with the competence 
I have now. I would love to create a proof quantifying the probability of initialized decision boundaries by area and
investigate whether "difficult" data (such as data requiring more principal components) lags behind in class convergence. 
But such is the way of hindsight and research, and I learned a lot from the experience. I also worked very independently, 
which helped develope my confidence and made me feel comfortable to take on new research projects on my own.

---

[**Paper (PDF)**](/assets/pdf/Brown_paper.pdf) &nbsp;·&nbsp; [**Poster (PDF)**](/assets/pdf/Brown_paper.pdf) &nbsp;·&nbsp; [**Code (GitHub)**](https://github.com/JackForeback/CIR)
