---
title: "Predicting Yelp Star Reviews Based on Network Structure with Deep Learning"
collection: publications
permalink: /publication/2017-12-11-yelp-reviews
excerpt: 'In this paper, we tackle the real-world problem of predicting Yelp star-review rating based on business features (such as images, descriptions), user features (average previous ratings), and, of particular interest, network properties (which businesses has a user rated before).'
date: 2017-12-11
venue: 'arxiv'
paperurl: 'https://arxiv.org/abs/1712.04350'
citation: 'L Perez - arXiv preprint arXiv:1712.04350, 2017'
---

In this paper, we tackle the real-world problem of predicting Yelp star-review rating based on business features (such as images, descriptions), user features (average previous ratings), and, of particular interest, network properties (which businesses has a user rated before). We compare multiple models on different sets of features -- from simple linear regression on network features only to deep learning models on network and item features. In recent years, breakthroughs in deep learning have led to increased accuracy in common supervised learning tasks, such as image classification, captioning, and language understanding. However, the idea of combining deep learning with network feature and structure appears to be novel. While the problem of predicting future interactions in a network has been studied at length, these approaches have often ignored either node-specific data or global structure. We demonstrate that taking a mixed approach combining both node-level features and network information can effectively be used to predict Yelp-review star ratings. We evaluate on the Yelp dataset by splitting our data along the time dimension (as would naturally occur in the real-world) and comparing our model against others which do no take advantage of the network structure and/or deep learning.

[Download](/files/1712.04350.pdf)