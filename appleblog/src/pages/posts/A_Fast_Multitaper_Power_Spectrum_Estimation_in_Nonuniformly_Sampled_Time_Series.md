---
layout: '../../layouts/MarkdownPost.astro'
title: 'A Fast Multitaper Power Spectrum Estimation in Nonuniformly Sampled Time Series'
pubDate: 2024-07-09 04:41:40
description: ''
author: 'wanghaisheng'
cover:
    url: 'https://www.apple.com.cn/newsroom/images/product/homepod/standard/Apple-HomePod-hero-230118_big.jpg.large_2x.jpg'
    square: 'https://www.apple.com.cn/newsroom/images/product/homepod/standard/Apple-HomePod-hero-230118_big.jpg.large_2x.jpg'
    alt: 'cover'
tags: ['all search terms'] 
theme: 'light'
featured: true

meta:
 - name: author
   content: Jie Cui et.al.
 - name: keywords
   content: key3, key4

keywords: key1, key2, key3
---

## paper id
2407.01943v2
## download
[2407.01943v2](http://arxiv.org/abs/2407.01943v2)
## abstracts:
Nonuniformly sampled signals are prevalent in real-world applications but pose a significant challenge when estimating their power spectra from a finite number of samples of a single realization. The optimal solution using Bronez Generalized Prolate Spheroidal Sequence (GPSS) is computationally intensive and thus impractical for large datasets. This paper presents a fast nonparametric method, MultiTaper NonUniform Fast Fourier Transform (MTNUFFT), capable of estimating power spectra with lower computational burden. The method first derives a set of optimal tapers via cubic spline interpolation on a nominal analysis band, and subsequently shifts these tapers to other analysis bands using NonUniform FFT (NUFFT). The estimated spectral power within the band is the average power at the outputs of the taper set. This algorithm eliminates the time-consuming computation for solving the Generalized Eigenvalue Problem (GEP), thus reducing the computational load from $O(N^4)$ to $O(N \log N + N \log(1/\epsilon))$, comparable with the NUFFT. The statistical properties of the estimator are assessed using Bronez GPSS theory, revealing that the bias and variance bound of the MTNUFFT estimator are identical to those of the optimal estimator. Furthermore, the degradation of bias bound can serve as a measure of the deviation from optimality. The performance of the estimator is evaluated using both simulation and real-world data, demonstrating its practical applicability. The code of the proposed fast algorithm is available on GitHub (https://github.com/jiecui/mtnufft).
## QA:
coming soon
