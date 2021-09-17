---
layout: post
title: Kullback–Leibler divergence
subtitle: Information loss in distribution approximation 
#cover-img: /assets/img/path.jpg
#thumbnail-img: /assets/img/measure-1509707_640.jpg
#share-img: /assets/img/path.jpg
tags: [probability theory, information theory]
---

> To measure the difference between two probability distributions over the same
variable x, a measure, called the Kullback-Leibler divergence, or simply, the KL
divergence, has been popularly used in the data mining literature. The concept
was originated in probability theory and information theory.
The KL divergence, which is closely related to relative entropy, information divergence, and information for discrimination, is a non-symmetric measure of the difference between two probability distributions p(x) and q(x).
Specifically, the Kullback-Leibler (KL) divergence of q(x) from p(x), denoted
DKL(p(x), q(x)), is a measure of the information lost when q(x) is used to approximate p(x). Typically p(x) represents the “true” distribution of data,
observations, or a precisely calculated theoretical distribution. The measure
q(x) typically represents a theory, model, description, or approximation of p(x).

[Kullback-Leibler Divergence](http://hanj.cs.illinois.edu/cs412/bk3/KL-divergence.pdf)

> In machine learning and neuroscience the KL divergence
also plays a leading role. In Bayesian machine learning,
it is typically used to approximate an intractable density
model. For example, expectation propagation [16] iteratively
approximates an exponential family model to the desired
density, minimising the inclusive KL divergence: D(P||Papp).
While variational methods [15] minimize the exclusive KL
divergence, D(Papp||P), to fit the best approximation to P.

[Kullback-Leibler Divergence Estimation of
Continuous Distributions](http://www.tsc.uc3m.es/~fernando/bare_conf3.pdf)

 By: Alex Javidi
