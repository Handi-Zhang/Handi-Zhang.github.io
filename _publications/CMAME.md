---
title: "Reliable extrapolation of deep neural operators informed by physics or sparse observations"
collection: publications
permalink: /publication/CMAME/
date: 2023-07-01
venue: 'Computer Methods in Applied Mechanics and Engineering, Volume 412, 1 July 2023, 116064'
paperurl: https://www.sciencedirect.com/science/article/abs/pii/S0045782523001883
excerpt: ""
---

## Abstract

Deep neural operators can learn nonlinear mappings between infinite-dimensional function spaces via deep neural networks. As promising surrogate solvers of partial differential equations (PDEs) for real-time prediction, deep neural operators such as deep operator networks (DeepONets) provide a new simulation paradigm in science and engineering. Pure data-driven neural perators and deep learning models, in general, are usually limited to interpolation scenarios, where new predictions utilize inputs within the support of the training set. However, in the inference stage of real-world applications, the input may lie outside the support, i.e., extrapolation is required, which may result to large errors and unavoidable failure of deep learning models. Here, we address this challenge of extrapolation for deep neural operators. First, we systematically investigate the extrapolation behavior of DeepONets by quantifying the extrapolation complexity via the 2-Wasserstein distance between two function spaces and propose a new strategy of bias-variance trade-off for extrapolation with respect to model capacity. Subsequently, we develop a complete workflow, including extrapolation determination, and we propose five reliable learning methods that guarantee a safe prediction under extrapolation by requiring additional information—the governing PDEs of the system or sparse new observations. The proposed methods are based on either fine-tuning a pre-trained DeepONet or multifidelity learning. We demonstrate the effectiveness of the proposed framework for various types of parametric PDEs. Our systematic comparisons provide practical guidelines for selecting a proper extrapolation method depending on the available information, desired accuracy, and required inference speed.
