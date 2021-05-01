---
title: Robust Detection of Network Intrusion using Tree-based Convolutional Neural Networks
summary: A Tree based CNN architecture to detect network intrusions
tags:
- Deep Learning
date: "20-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Proposed framework
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: 
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

We explore the use of neural networks in network intrusion detection using the popular [NSL-KDD](https://www.unb.ca/cic/datasets/nsl.html) dataset. We propose an incremental learning model called the TreeNets to identify network intrusions. The model is a tree with each node carrying a CNN. The tree grows while training depending on the number of classes and how the data trains. We achieve results that are better than or on par with the state-of-the-art models in this field as of 2020. The paper on this project was accepted in CODS-COMAD 2021. You can find the paper [here](https://dl.acm.org/doi/abs/10.1145/3430984.3431036).