---
layout: '../../layouts/MarkdownPost.astro'
title: 'Self-supervised Vision Transformer are Scalable Generative Models for Domain Generalization'
pubDate: 2024-07-09 04:41:39
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
   content: Sebastian Doerrich et.al.
 - name: keywords
   content: key3, key4

keywords: key1, key2, key3
---

## paper id
2407.02900v1
## download
[2407.02900v1](http://arxiv.org/abs/2407.02900v1)
## abstracts:
Despite notable advancements, the integration of deep learning (DL) techniques into impactful clinical applications, particularly in the realm of digital histopathology, has been hindered by challenges associated with achieving robust generalization across diverse imaging domains and characteristics. Traditional mitigation strategies in this field such as data augmentation and stain color normalization have proven insufficient in addressing this limitation, necessitating the exploration of alternative methodologies. To this end, we propose a novel generative method for domain generalization in histopathology images. Our method employs a generative, self-supervised Vision Transformer to dynamically extract characteristics of image patches and seamlessly infuse them into the original images, thereby creating novel, synthetic images with diverse attributes. By enriching the dataset with such synthesized images, we aim to enhance its holistic nature, facilitating improved generalization of DL models to unseen domains. Extensive experiments conducted on two distinct histopathology datasets demonstrate the effectiveness of our proposed approach, outperforming the state of the art substantially, on the Camelyon17-wilds challenge dataset (+2%) and on a second epithelium-stroma dataset (+26%). Furthermore, we emphasize our method's ability to readily scale with increasingly available unlabeled data samples and more complex, higher parametric architectures. Source code is available at https://github.com/sdoerrich97/vits-are-generative-models .
## QA:
coming soon
