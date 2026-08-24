---
layout: page
title: LeDreamer
description: Regularized Joint Embeddings for Minecraft
img: assets/img/project_imgs/lejepa.jpg
importance: 1
category: research
---

I did this research in January of 2026 for a class, but it was something I wanted to do regardless. As has become 
a theme for my projects, I was exploring research areas for my PhD and got very interested in self supervised 
learning. My previous REU advisor from Brown, Dr. Randall Balestriero, had proposed adding joint embeddings to 
dreamer4 in his slack. I took up the project on my own.

Sadly, I did not have the compute to reproduce the experiments run by Google, who used 1024 TPUs. I instead ran a  
restricted subset of experiments on only 300 hours of the training data with a smaller model. These experiments 
still showed promising results, but I then had to transition into work on my REU summer project at RIT. All of the 
code to run the experiments is still on my Github, and videos of the pretrained models can be seen on my Youtube 
channel, [here]().

Also, big thanks to [lucidrains](https://github.com/lucidrains/dreamer4), who created the dreamer4 repository used 
to create and test LeDreamer.

---

[**Poster (PDF)**](/assets/pdf/lejepa_poster.pdf) &nbsp;·&nbsp; [**Code (GitHub)**](https://github.com/JackForeback/LeDreamer-mc)
