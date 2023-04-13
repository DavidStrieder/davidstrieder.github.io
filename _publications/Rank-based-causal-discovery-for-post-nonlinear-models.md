---
title: "Rank-based causal discovery for post-nonlinear models"
collection: publications
permalink: /publication/Rank-based-causal-discovery-for-post-nonlinear-models
date: 1 April 2023
venue: 'Proceedings of Machine Learning Research'
paperurl: 'https://proceedings.mlr.press/v206/keropyan23a.html'
citation: 'G. Keropyan, D. Strieder and M. Drton. <i> Rank-Based Causal Discovery for Post-Nonlinear Models </i> 
Proceedings of The 26th International Conference on Artificial Intelligence and Statistics, PMLR 206:7849-7870, (2023).'


---


Learning causal relationships from empirical observations is a central task in scientific research. A common method is to employ structural causal models that postulate noisy functional relations among a set of interacting variables. To ensure unique identifiability of causal directions, researchers consider restricted subclasses of structural causal models. Post-nonlinear (PNL) causal models constitute one of the most flexible options for such restricted subclasses, containing in particular the popular additive noise models as a further subclass. However, learning PNL models is not well studied beyond the bivariate case. The existing methods learn non-linear functional relations by minimizing residual dependencies and subsequently test independence from residuals to determine causal orientations. However, these methods can be prone to overfitting and, thus, difficult to tune appropriately in practice. As an alternative, we propose a new approach for PNL causal discovery that uses rank-based methods to estimate the functional parameters. This new approach exploits natural invariances of PNL models and disentangles the estimation of the non-linear functions from the independence tests used to find causal orientations. We prove consistency of our method and validate our results in numerical experiments.


[Download paper here](https://proceedings.mlr.press/v206/keropyan23a.html)

