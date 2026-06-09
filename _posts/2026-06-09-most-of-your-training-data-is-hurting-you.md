---
layout: post
title: "Most of your training data is hurting you"
---

When we started working on CRAFT, the assumption I had to unlearn was that more parallel data means better translation. Web-mined corpora like WikiMatrix contain tens of millions of English–Hindi pairs, but a large share of them are misaligned, machine-translated, or simply irrelevant to the domain you actually care about.

The interesting question isn't *how much* data you have — it's *which* data matches the distribution you'll be evaluated on. In an upcoming post I'll walk through how we framed this as a distribution-matching problem: cluster the source side, allocate a selection budget proportionally to the validation distribution, then use conditional regression on the target side to pick the pairs worth fine-tuning on.

If you want to skip ahead, the paper is [on arXiv](https://arxiv.org/abs/2604.22693).
