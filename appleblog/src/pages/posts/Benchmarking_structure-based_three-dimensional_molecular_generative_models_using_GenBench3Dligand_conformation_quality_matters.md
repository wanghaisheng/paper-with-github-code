---
layout: '../../layouts/MarkdownPost.astro'
title: 'Benchmarking structure-based three-dimensional molecular generative models using GenBench3D: ligand conformation quality matters'
pubDate: 2024-07-09 04:41:37
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
   content: Benoit Baillif et.al.
 - name: keywords
   content: key3, key4

keywords: key1, key2, key3
---

## paper id
2407.04424v1
## download
[2407.04424v1](http://arxiv.org/abs/2407.04424v1)
## abstracts:
Three-dimensional (3D) deep molecular generative models offer the advantage of goal-directed generation based on 3D-dependent properties, such as binding affinity for structure-based design within binding pockets. Traditional benchmarks created to evaluate SMILES or molecular graphs generators, such as GuacaMol or MOSES, are limited to evaluate 3D generators as they do not assess the quality of the generated molecular conformation. In this work, we hence developed GenBench3D, which implements a new benchmark for models producing molecules within a binding pocket. Our main contribution is the Validity3D metric, evaluating the conformation quality using the likelihood of bond lengths and valence angles based on reference values observed in the Cambridge Structural Database. The LiGAN, 3D-SBDD, Pocket2Mol, TargetDiff, DiffSBDD and ResGen models were benchmarked. We show that only between 0% and 11% of generated molecules have valid conformations. Performing local relaxation of generated molecules in the pocket considerably improved the Validity3D for all models by a minimum increase of 40%. For LiGAN, 3D-SBDD, or TargetDiff, the set of valid relaxed molecules shows on average higher Vina score (i.e. worse) than the set of raw generated molecules, indicating that the binding affinity of raw generated molecules might be overestimated. Using the other scoring functions, that give higher importance to ligand strain, only yield improved scores when using valid relaxed molecules. Using valid relaxed molecules, TargetDiff and Pocket2Mol show better median Vina, Glide and Gold PLP scores than other models. We have publicly released GenBench3D on GitHub for broader use: https://github.com/bbaillif/genbench3d
## QA:
coming soon
