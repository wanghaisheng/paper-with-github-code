---
layout: '../../layouts/MarkdownPost.astro'
title: 'Example-Based Automatic Migration of Continuous Integration Systems'
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
   content: Dhia Elhaq Rzig et.al.
 - name: keywords
   content: key3, key4

keywords: key1, key2, key3
---

## paper id
2407.02644v1
## download
[2407.02644v1](http://arxiv.org/abs/2407.02644v1)
## abstracts:
Continuous Integration (CI) is a widely adopted practice for faster code change integration and testing. Developers often migrate between CI systems in pursuit of features like matrix building or better logging. However, this migration is effort intensive and error-prone owing to limited knowledge of the new CI system and its syntax. Moreover, these migrations require multiple iterations and significant time to achieve stability in the new CI system, and there is insufficient support for the automatic migration of CI configurations.   To mitigate this, we propose a novel approach for CI system's automatic migration: CIMig. Our approach utilizes Example-Based mining, where it extracts translation rules and configuration patterns from existing migration examples, and employs them to reproduce this migration in new contexts. To empirically validate and evaluate our approach, we apply it to the migration between Travis CI and GitHub Actions. We gathered learnings from 1001 projects, and then applied them to migrate an evaluation set of 251 projects. This helped us perform a qualitative and quantitative evaluation of CIMig, and we contextualize our results by comparing them with those of the manual-rule-based GitHub Actions Importer. Furthermore, our tool generated files that were rated favorably by developers and saved them an average of 42.4 minutes over the manual migration of these same projects. Our learning-based approach is also more flexible, as proven by our ability to apply it to migrate GitHub Actions files to Travis, which GitHub Actions Importer can not do. We believe CIMig is the first approach of its kin to migrate CI systems and can be applied to other software configuration system migrations. Our replication package is available at [5].
## QA:
coming soon
