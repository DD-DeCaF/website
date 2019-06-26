---
layout: publication
title: NG-meta-profiler - fast processing of metagenomes using NGLess, a domain-specific language
authors: Coelho, L.P. and Alves, R. and Monteiro, P. and Huerta-Cepas, J. and Freitas, A.T. and Bork, P.
journal: Microbiome
volume: 7
number: 1
pages: 84
year: 2019
doi: 10.1186/s40168-019-0684-8
icon: mdi-file-document
---
Background
Shotgun metagenomes contain a sample of all the genomic material in an environment, allowing for the characterization of a microbial community. In order to understand these communities, bioinformatics methods are crucial. A common first step in processing metagenomes is to compute abundance estimates of different taxonomic or functional groups from the raw sequencing data.
Given the breadth of the field, computational solutions need to be flexible and extensible, enabling the combination of different tools into a larger pipeline.
Results
We present NGLess and NG-meta-profiler. NGLess is a domain specific language for describing next-generation sequence processing pipelines. It was developed with the goal of enabling user-friendly computational reproducibility. It provides built-in support for many common operations on sequencing data and is extensible with external tools with configuration files.
Using this framework, we developed NG-meta-profiler, a fast profiler for metagenomes which performs sequence preprocessing, mapping to bundled databases, filtering of the mapping results, and profiling (taxonomic and functional). It is significantly faster than either MOCAT2 or htseq-count and (as it builds on NGLess) its results are perfectly reproducible.
Conclusions
NG-meta-profiler is a high-performance solution for metagenomics processing built on NGLess. It can be used as-is to execute standard analyses or serve as the starting point for customization in a perfectly reproducible fashion.
NGLess and NG-meta-profiler are open source software (under the liberal MIT license) and can be downloaded from https://ngless.embl.de or installed through bioconda.