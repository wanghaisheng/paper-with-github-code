---
layout: '../../layouts/MarkdownPost.astro'
title: 'MotifbreakR v2: extended capability and database integration'
pubDate: 2024-07-09 04:41:38
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
   content: Simon G. Coetzee et.al.
 - name: keywords
   content: key3, key4

keywords: key1, key2, key3
---

## paper id
2407.03441v1
## download
[2407.03441v1](http://arxiv.org/abs/2407.03441v1)
## abstracts:
MotifbreakR is a software tool that scans genetic variants against position weight matrices of transcription factors (TF) to determine the potential for the disruption of TF binding at the site of the variant. It leverages the Bioconductor suite of software packages and annotations to operate across a diverse array of genomes and motif databases. Initially developed to interrogate the effect of single nucleotide variants (common and rare SNVs) on potential TF binding sites, in motifbreakR v2, we have updated the functionality. New features include the ability to query other types of more complex genetic variants, such as short insertions and deletions (indels). This function allows modeling a more extensive array of variants that may have more significant effects on TF binding. Additionally, while TF binding is based partly on sequence preference, predictions of TF binding based on sequence preference alone can indicate many more potential binding events than observed. Adding information from DNA-binding sequencing datasets lends confidence to motif disruption prediction by demonstrating TF binding in cell lines and tissue types. Therefore, motifbreakR implements querying the ReMap2022 database for evidence that a TF matching the disrupted motif binds over the disrupting variant. Finally, in motifbreakR, in addition to the existing interface, we have implemented an R/Shiny graphical user interface to simplify and enhance access to researchers with different skill sets.
## QA:
coming soon
