---
title: "Fair Associative Co-Clustering"
collection: publications
category: phd_thesis
permalink: /publication/2026-phd-thesis
date: 2026-07-23
venue: "University of Turin"
paperurl: "https://iris.unito.it/handle/2318/2153570"
authors: "Peiretti, F. (2026)"
abstract: >
  Co-clustering is a powerful data mining technique designed to extract summary information from data matrices by simultaneously grouping rows and columns. By exploiting latent relationships between objects and their attributes, co-clustering provides a compact representation of the data, identifying coherent groups of similar instances and their interactions with clusters of correlated features. This approach has demonstrated effectiveness across a wide range of real-world applications, including gene expression analysis, text mining, recommender systems, market basket analysis, and community detection. In this dissertation, we address the problem of co-clustering in sparse, high-dimensional contingency tables, with a particular focus on algorithmic fairness. Although fairness has been extensively studied in supervised learning and clustering, it has received only limited attention in co-clustering. Ensuring fairness is crucial when co-clustering methods are employed in decision-making processes involving sensitive attributes such as gender or ethnicity, since resulting co-clusters may have under- or over-represented social groups, potentially leading to discrimination against minorities. To mitigate such risks, we introduce a formal definition of fair co-clustering, where a co-clustering algorithm ensures group fairness if each co-cluster preserves the same proportion of protected groups as in the overall dataset — capturing the concept of balance in the context of fair clustering. Building on this definition, we propose a novel fair co-clustering algorithm, called Fair-$\tau$CC, based on an associative measure derived from Goodman–Kruskal's $\tau$, which exhibits favorable convergence properties. The algorithm is parameterless (it does not require specifying the final number of row and column clusters) and achieves a good trade-off between fairness and clustering quality. Moreover, Fair-$\tau$CC supports fairness constraints involving two or more protected groups and can enforce fairness not only across row clusters but also across column clusters, when protected group information for the columns is also available.
---

**Author:** Federico Peiretti

**Ph.D. Thesis**, University of Turin, July 23, 2026.

**Link:** [iris.unito.it/handle/2318/2153570](https://iris.unito.it/handle/2318/2153570)
