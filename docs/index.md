---
layout: default
title: Home
header: Machine Learning from Time Series
nav_order: 1
---

## Overview

Time series classification (TSC) is a rapidly evolving field with applications across all domains of machine learning and data science. This tutorial provides an accessible overview of the recent research in TSC and includes interactive examples via Jupyter notebooks. We introduce a taxonomy of TSC algorithms and describe the temporal features they extract. We highlight some of the issues practitioners face when formulating a TSC problem, and give guidance on how to best overcome them. This includes handling data characteristics such as segmenting data, class imbalance, unequal length series and high dimensionality. The latest advances in the field of time series classification are all available through the [_aeon_](https://www.aeon-toolkit.org) toolkit, an open source, [_scikit-learn_](https://scikit-learn.org/) compatible framework for time series machine learning which we use in our code examples.

## When & Where

- Conference: [DSAA 2025](https://dsaa.ieee.org/2025/)
- Date: Sunday, October 12
- Time: 09:00 - 12:00 
- Room: Lloyd Suite

## Prerequisites

This tutorial is aimed at those interested in time series machine learning (TSML) research, with a focus on classification with ordered data.

- Basic machine learning background
- For code examples: Basic understanding of programming in Python and/or Jupyter notebooks 

## Background

Time series classification (TSC) \[[1](https://doi.org/10.1007/s10618-016-0483-9),[2](https://doi.org/10.1007/s10618-024-01022-1)\] involves fitting a model from a continuous, ordered sequence of real valued observations (a time series) to a discrete response variable. Time series (TS) can be univariate (a single variable at each time point) or multivariate (multiple variables at each time point) \[[3](https://doi.org/10.1007/s10618-020-00727-3)\]. TSC problems come from various domains, including medical signals such as electroencephalogram; Human activity recognition; audio; electricity usage; and many more with industrial and scientific applications. While usually formatted into a clean and equal length structure for research \[[4](https://doi.org/10.1109/JAS.2019.1911747)\], the datasets generated for many of these applications are imperfect in practice. Some of the characteristics of an imperfect TS dataset are: missing values, unequal length series, significant class imbalance, and/or extreme dimensionality. Some data may start naturally unsegmented as a TS stream rather than the collection of cases required for classification. 

In this tutorial we highlight how we learn from TS data using the latest algorithms \[[2](https://doi.org/10.1007/s10618-024-01022-1)\], and why these techniques are preferable to more traditional machine learning approaches. We group algorithms by the representation used to differentiate between types of features extracted from series. Our first objective is to give researchers and practitioners an overview of TSC research and how informative features are extracted from TS data. Our second objective is to equip attendees with an understanding of how to recognise and process imperfect TS data for TSC. This is not a trivial task, and misusing certain preprocessing steps can significantly impact model results.

## References

[[1]](https://doi.org/10.1007/s10618-016-0483-9) __Anthony Bagnall__, Jason Lines, Aaron Bostrom, James Large, and Eamonn Keogh. The great time series classification bake off: a review and experimental evaluation of recent algorithmic advances. Data Mining and Knowledge Discovery, 31(3):606–660, 2017.

[[2]](https://doi.org/10.1007/s10618-024-01022-1) __Matthew Middlehurst__, Patrick Schäfer, and __Anthony Bagnall__. Bake off redux: a review and experimental evaluation of recent time series classification algorithms. Data Mining and Knowledge Discovery, 1-74, 2024.

[[3]](https://doi.org/10.1007/s10618-020-00727-3) Alejandro Pasos Ruiz, Michael Flynn, James Large, __Matthew Middlehurst__, and __Anthony Bagnall__. The great multivariate time series classification bake off: a review and experimental evaluation of recent algorithmic advances. Data Mining and Knowledge Discovery, 401-449, 2021.

[[4]](https://doi.org/10.1109/JAS.2019.1911747) Hoang Anh Dau, __Anthony Bagnall__, Kaveh Kamgar, Chin-Chia Michael Yeh, Yan Zhu, Shaghayegh Gharghabi, Chotirat Ann Ratanamahatana, and Eamonn Keogh. The UCR time series archive. IEEE/CAA Journal of Automatica Sinica, 1293-1305, (2019).
