---
abstract: Networks of genetic expression can be modeled by hypergraphs with the additional structure that real coefficients are given to each vertex-edge incidence. The spectra, i.e. the multiset of the eigenvalues, of such hypergraphs, are known to encode structural information of the data. We show how these spectra can be used, in particular, in order to give an estimation of cellular redundancy, a novel measure of gene expression heterogeneity, of the network. We analyze some simulated and real data sets of gene expression for illustrating the new method proposed here.
authors:
- Raffaella Mulas
- Michael J. Casey
date: "2021-11-01"
doi: "10.1016/j.mbs.2021.108713"
featured: false
publication: In *Mathematical Biosciences*
publication_short: In *Mathematical Biosciences*
publication_types:
- "1"
publishDate: "2021-11-01"
summary: Networks of genetic expression can be modeled by hypergraphs with the additional structure that real coefficients are given to each vertex-edge incidence. The spectra, i.e. the multiset of the eigenvalues, of such hypergraphs, are known to encode structural information of the data. We show how these spectra can be used, in particular, in order to give an estimation of cellular redundancy, a novel measure of gene expression heterogeneity, of the network. We analyze some simulated and real data sets of gene expression for illustrating the new method proposed here.
tags:
- scRNA-seq
- Hypergraphs
title: Estimating cellular redundancy in networks of genetic expression
url_code: https://github.com/mjcasy/scHyperGraph
---

Networks of genetic expression can be modeled by hypergraphs with the additional structure that real coefficients are given to each vertex-edge incidence. The spectra, i.e. the multiset of the eigenvalues, of such hypergraphs, are known to encode structural information of the data. We show how these spectra can be used, in particular, in order to give an estimation of cellular redundancy, a novel measure of gene expression heterogeneity, of the network. We analyze some simulated and real data sets of gene expression for illustrating the new method proposed here.

**My Involvement:** Please see the HyperEigen.py file in the code repository for my sparse implementation of spectral hypergraph calculations. This is an adaptation of the code found in the rhype package but optimised to quickly run on large matrices with few entries.
