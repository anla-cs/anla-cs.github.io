---
title: "Dynamic Locality Sensitive Orderings in Doubling Metrics"
date: 2025-06-15
publishDate:  2025-06-15
authors: ["**An La**", "Hung Le"]
publication_types: ["2"]
abstract: "This version has 12 pages. Click [here](https://arxiv.org/abs/2408.14617) for the full version."
featured: true
publication: ""
links:
  - icon_pack: fas
    icon: scroll
    name: https://dl.acm.org/doi/10.1145/3717823.3718209
    url: 'https://dl.acm.org/doi/10.1145/3717823.3718209'
---
Click [here](https://arxiv.org/abs/2408.14617) for the full version.

**Abstract**:
In their pioneering work, Chan, Har-Peled, and Jones (SICOMP 2020) introduced locality-sensitive ordering (LSO), and constructed an LSO with a constant number of orderings for point sets in the d-dimensional Euclidean space. Furthermore, their LSO could be made dynamic effortlessly under point insertions and deletions, taking O(logn) time per update by exploiting Euclidean geometry. Their LSO provides a powerful primitive to solve a host of geometric problems in both dynamic and static settings. Filtser and Le (STOC 2022) constructed the first LSO with a constant number of orderings in the more general setting of doubling metrics. However, their algorithm is inherently static since it relies on several sophisticated constructions in intermediate steps, none of which is known to have a dynamic version. Making their LSO dynamic would recover the full generality of LSO and provide a general tool to dynamize a vast number of static constructions in doubling metrics.
In this work, we give a dynamic algorithm that has O(logn) time per update to construct an LSO in doubling metrics under point insertions and deletions. We introduce a toolkit of several new data structures: a pairwise tree cover, a net tree cover, and a leaf tracker. A key technical is stabilizing the dynamic net tree of Cole and Gottlieb (STOC 2006), a central dynamic data structure in doubling metrics. Specifically, we show that every update to the dynamic net tree can be decomposed into a few simple updates to trees in the net tree cover. As stability is the key to any dynamic algorithm, our technique could be useful for other problems in doubling metrics.
We obtain several algorithmic applications from our dynamic LSO. The most notably is the first dynamic algorithm for maintaining an k-fault tolerant spanner in doubling metrics with optimal sparsity in optimal O(logn) time per update.

