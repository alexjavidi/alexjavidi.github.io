---
layout: post
title: Model Complexity
subtitle: Why goodness of fit is necessary but not sufficient
#cover-img: /assets/img/path.jpg
#thumbnail-img: /assets/img/measure-1509707_640.jpg
#share-img: /assets/img/path.jpg
tags: [statistics, model complexity]
---

> An improper choice of model or method can lead to purely noisy “discoveries”, severely misleading
conclusions, or disappointing predictive performances. Therefore, a crucial step in a typical data analysis is
to consider a set of candidate models (referred to as the model class), and then select the most appropriate one.
In other words, model selection is the task of selecting a statistical model from a model class, given a set of data.

[Model Selection Techniques-An Overview](https://arxiv.org/pdf/1810.09583.pdf)


> While the goal of mathematical modeling in cognitive psychology is to select one
model from a set of competing models that best captures the underlying mental
process, the researcher often chooses the model that best fits a particular set of
data. Presumably, the justification for this procedure is that the model providing
the best fit (e.g., the one that accounts for the most variance) is the one that most
closely approximates the underlying mental process. In fact, this justification is
unwarranted, for a highly complex model can provide a good fit without necessarily
bearing any interpretable relationship with the underlying process

> Complexity affects not only model fit but also the generalizability of a model and
the variability in parameter estimation. It is therefore necessary to consider them
when evaluating models. A simple model will generalize better to new data sets than
a complex model and thus will have a higher degree of predictive accuracy. In addition, a simple model's behavior is more tractable because parameter estimates will
be more stable after repeated data fittings than those of complex models.

> A central theme of model selection is that to avoid choosing unnecessarily complex models, a model should be selected based on its generalizability, rather than
its goodness of fit. This goal is realized by defining a selection criterion that makes
an appropriate adjustment to its goodness of fit by taking into account the contribution from model complexity. There are at least seven different selection
methods that are currently in use. They differ from one another in terms of how
such adjustments are made to best estimate a model's generalizability

[The Importance of Complexity in Model Selection](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.549.1687&rep=rep1&type=pdf)


> Understanding the complexity of a deep model is a key
to precisely understanding the capability and limitation of the model. Exploring
model complexity is necessary not only for understanding a deep model itself,
but also for investigating many other related fundamental questions. For example, from the statistical learning theory point of view, the expressive power of a
model is used to bound the generalization error [69]. Some recent studies propose norm-based model complexity [60] and sensitivity-based model complexity [76, 81] to explore the generalization capability of deep models. Moreover,
detecting changes of model complexity in a training process can provide insights
into understanding and improving the performance of model optimization and
regularization [44, 74, 89].

[Model Complexity of Deep Learning: A Survey](https://arxiv.org/abs/2103.05127)


 By: Alex Javidi
