---
title: "Structure-Preserving Neural Surrogates with Tractable Uncertainty Quantification"
collection: publications
permalink: /publication/UQ/
date: 2026-6-10
venue: 'arXiv Preprint'
paperurl: https://arxiv.org/abs/2606.11650

---

## Abstract
Recent advances in scientific machine learning provide a means of near-real-time solution to partial differential equations (PDEs), but lack the theoretical underpinnings of conventional simulators that support contemporary validation. In this work, we construct data-driven reduced-order models that serve as structure-preserving, real-time surrogates. Remarkably, the exterior calculus exposes topological structure for building a Gaussian process (GP) representation of state-flux uncertainty, ultimately yielding a Dirichlet-to-Neumann map for quantities of interest with closed-form expressions for posterior uncertainty. We specifically propose structure-preserving Hdiv-L2 subspaces of Raviart--Thomas and $dgP_0$ elements prescribed by a transformer. Reduced-order dynamics consistent with this subspace are learned by posing a conservation law where a GP describes the fluxes between volumes. This work hinges on a novel interface between mixed FEM spaces and GP regression; when training is posed as the optimal recovery problem (ORP), the resulting GP regression can be written as an optimization problem with equality constraints that impose a conservation structure, amenable to a fast Schur-complement solve. The trained model can then be solved with closed-form estimators for boundary fluxes driven by prescribed Dirichlet data. The paper includes RKHS posterior error bounds to support uncertainty quantification, as well as numerical experiments showing the accuracy of the posterior distribution as a surrogate for error estimation.
