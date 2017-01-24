---
layout: post
comments: true
tags:
- ml
- notes
- NIPS
title: Notes from a NIPS 2016 summary
---

Notes on [Andreas Stuhlmüller](https://blog.ought.com/nips-2016-875bb8fadb8c#.b0ye6ifs8)

- How to make ML work better when we have limited amount of 'real' environment data. For example: we may have a large set of general speech data, but a limited set of in car speech data.

- One possible reason why deep NN works despite local minima problems could be because of over provisioning. Related not: From Kawaguchi, in deep NN all local minima are global minima. The only problem areas are saddle points.

- Regularizing and hyper parameter optimization using Bayesian approach. I thought David Mackay and Radford Neal did this long time back (?). Should read about connections between Gaussian process and Neural nets

- Why and when do GANs work better than variational Autoencoders ?

- Big open problems in GANs:
  1. Will the minimax game between discriminator and generator reach an equilbrium ?
  2. GANs for discrete and sequential problems
  3. Global structure and GANs (I don't understand this)

- Datasets for dialog systems:
  1. https://research.fb.com/projects/babi/
  2. https://www.kaggle.com/c/the-allen-ai-science-challenge
  3. The Ubuntu dataset: https://arxiv.org/abs/1506.08909

- Learning to learn
   - https://arxiv.org/abs/1606.04474

- NNets are inherently discrete (# of layers, # of neurons, connections, etc) 
  Can there be Analog Neural Nets ?
