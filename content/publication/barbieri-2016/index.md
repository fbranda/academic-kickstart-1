---
title: "Efficient Methods for Influence-Based Network-Oblivious Community Detection"
date: 2016-12-01
publishDate: 2019-09-07T09:18:44.894266Z
authors: ["Nicola Barbieri", "Francesco Bonchi", "Giuseppe Manco"]
publication_types: ["2"]
abstract: "We study the problem of detecting social communities when the social graph is not available but instead we have access to a log of user activity, that is, a dataset of tuples (u, i, t) recording the fact that user u “adopted” item i at time t. We propose a stochastic framework that assumes that the adoption of items is governed by an underlying diffusion process over the unobserved social network and that such a diffusion model is based on community-level influence. That is, we aim at modeling communities through the lenses of social contagion. By fitting the model parameters to the user activity log, we learn the community membership and the level of influence of each user in each community. The general framework is instantiated with two different diffusion models, one with discrete time and one with continuous time, and we show that the computational complexity of both approaches is linear in the number of users and in the size of the propagation log. Experiments on synthetic data with planted community structure show that our methods outperform non-trivial baselines. The effectiveness of the proposed techniques is further validated on real-word data, on which our methods are able to detect high-quality communities."
featured: false
publication: "*ACM Transactions on Intelligent Systems and Technology*"
url_code: 'cwn_sources.zip'
doi: "10.1145/2979682"

tags: ["Social Influence", "Information Diffusion", "Social Network Analysis", "Community Detection", "Temporal Point Processes", "Generative Models"]
---

