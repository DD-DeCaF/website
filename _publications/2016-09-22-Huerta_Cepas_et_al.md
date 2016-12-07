---
layout: publication
title: Fast genome-wide functional annotation through orthology assignment by eggNOG-mapper
authors: Huerta-Cepas, Jaime and Forslund, Kristoffer and Szklarczyk, Damian and Jensen, Lars Juhl and von Mering, Christian and Bork, Peer
journal: bioRxiv
volume:
number:
pages: 076331
year: 2016
doi: 10.1101/076331
icon: mdi-file-document
---
Orthology assignment is ideally suited for functional inference. However, because predicting orthology is computationally intensive at large scale, and most pipelines relatively inaccessible, less precise homology-based functional transfer is still the default for (meta-)genome annotation. We therefore developed eggNOG-mapper, a tool for functional annotation of large sets of sequences based on fast orthology assignments using precomputed clusters and phylogenies from eggNOG. To validate our method, we benchmarked Gene Ontology predictions against two widely used homology-based approaches: BLAST and InterProScan. Compared to BLAST, eggNOG-mapper reduced by 7% the rate of false positive assignments, and increased by 19% the ratio of curated terms recovered over all terms assigned per protein. Compared to InterProScan, eggNOG-mapper achieved similar proteome coverage and precision, while predicting on average 32 more terms per protein and increasing by 26% the rate of curated terms recovered over total term assignments per protein. Through strict orthology assignments, eggNOG-mapper further renders more specific annotations than possible from domain similarity only (e.g. predicting gene family names). eggNOG-mapper runs ~15x than BLAST and at least 2.5x faster than InterProScan. The tool is available standalone or as an online service at http://eggnog-mapper.embl.de.
