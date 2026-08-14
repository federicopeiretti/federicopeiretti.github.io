---
title: "Fast parameterless prototype-based co-clustering"
collection: publications
category: manuscripts
permalink: /publication/2024-fast-parameterless-co-clustering
excerpt: "A parameterless prototype-based approach to co-clustering based on the Goodman–Kruskal's tau association measure."
date: 2024-04-01
venue: "Machine Learning"
paperurl: "https://doi.org/10.1007/s10994-023-06474-y"
abstract: "Tensor co-clustering algorithms have been proven useful in many application scenarios, such as recommender systems, biological data analysis and the analysis of complex and evolving networks. However, they are significantly affected by wrong parameter configurations, since, at the very least, they require the cluster number to be set for each mode of the matrix/tensor, although they typically have other algorithm-specific hyper-parameters that need to be fine-tuned. Among the few known objective functions that can be optimized without setting these parameters, the Goodman–Kruskal τ — a statistical association measure that estimates the strength of the link between two or more discrete random variables — has proven its effectiveness in complex matrix and tensor co-clustering applications. However, its optimization in a co-clustering setting is tricky and, so far, has leaded to very slow and, at least in some specific but not unfrequent cases, inaccurate algorithms, due to its normalization term. In this paper, we investigate some interesting mathematical properties of τ, and propose a new simplified objective function with the ability of discovering an arbitrary and a priori unspecified number of good-quality co-clusters. Additionally, the new objective function definition allows for a novel prototype-based optimization strategy that enables the fast execution of matrix and higher-order tensor co-clustering. We show experimentally that the new algorithm preserves or even improves the quality of the discovered co-clusters by outperforming state-of-the-art competing approaches, while reducing the execution time by at least two orders of magnitude."
citation: "Battaglia, E., Peiretti, F., & Pensa, R. G. (2024). Fast parameterless prototype-based co-clustering. Machine Learning, 113(4), 2153–2181."
authors:  "Battaglia, E., Peiretti, F., & Pensa, R. G. (2024)"
---

**Authors:** Elena Battaglia, Federico Peiretti, Ruggero G. Pensa

**Journal:** Machine Learning, 113(4), 2153–2181.

**DOI:** [10.1007/s10994-023-06474-y](https://doi.org/10.1007/s10994-023-06474-y)