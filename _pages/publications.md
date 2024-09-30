---
layout: archive
title: "Publications & Conferences"
permalink: /publications/
author_profile: true
---


Disentangled Structural and Featural Representation for Task-Agnostic Graph Valuation
------
Submitted to The 39th Annual AAAI Conference on Artificial Intelligence, 2024
__Ali Falahati__, Mohammad Mohammadi Amiri

With the emergence of data marketplaces, the demand for methods to assess the value of data has increased significantly. While numerous techniques have been proposed for this purpose, none have specifically addressed graphs as the main data modality. Graphs are widely used across various fields, ranging from chemical molecules to social networks. In this study, we break down graphs into two main components: structural and featural, and we focus on evaluating data without relying on specific task-related metrics, making it applicable in practical scenarios where validation requirements may be lacking. We introduce a novel framework called blind message passing, which aligns the seller's and buyer's graphs using a shared node permutation based on graph matching. This allows us to utilize the graph Wasserstein distance to quantify the differences in the structural distribution of graph datasets, called the structural disparities. We then consider featural aspects of buyers' and sellers' graphs for data valuation and capture their statistical similarities and differences, referred to as relevance and diversity, respectively. Our approach ensures that buyers and sellers remain unaware of each other's datasets. Our experiments on real datasets demonstrate the effectiveness of our approach in capturing the relevance, diversity, and structural disparities of seller data for buyers, particularly in graph-based data valuation scenarios.

[Download paper here](https://arxiv.org/abs/2408.12659)  


Natural Selection: A Natural Visibility Approach for Task-Agnostic Time Series Dataset Valuation
------
Preprint
__Ali Falahati__, Mohammad Mohammadi Amiri

Valuing time series datasets effectively is crucial for enhancing machine learning
models by selecting high-quality data that improves model performance. In this
paper, we propose a task-agnostic method for time series dataset valuation based on
a combination of local and global diversity measures. We first represent time series
as natural visibility graphs, transforming the data into a graph-based format. We
then compute local diversity through Weisfeiler-Lehman graph embeddings and
global diversity using the Gaussian Radial Basis Function (RBF) kernel, capturing
both local and global structure in the time series data. Our proposed true diversity
score, a convex combination of local and global diversity, provides a metric to
quantify the intrinsic variability of time series datasets. Additionally, we introduce
a relevance metric based on spectral graph entropy and Jensen-Shannon divergence,
which measures the similarity between time series datasets. This work contributes
to the growing field of data-centric AI by providing tools to assess the value of
time series data in a task-agnostic manner, facilitating better decision-making in
data selection for machine learning tasks.  

[Download draft here](https://ali-falahati.github.io/files/natural.pdf)  



Alter Ego: A Dedicated Blockchain Node For Analytics
------
Proceedings of the 7th International Workshop on Edge Systems, Analytics and Networking, 2024
Qi Guo, __Ali Falahati__, Mohammad Alizadeh, Laurent Bindschaedler

Blockchains today generate huge amounts of transaction data that need efficient real-time analytics for various applications like detecting smart contract hacks, performing arbitrage on decentralized exchanges, or analyzing trending tokens. However, conventional blockchain nodes and specialized ETL-based analytics systems struggle with a tradeoff between pre-calculating query results and analytical flexibility. To address this, we present AlterEgo, a blockchain node designed specifically for analytics. It can process consensus-produced blocks while providing a robust analytics API. Our prototype supports efficient transactional and analytical processing without the limitations of ETL workflows. It offers a more reliable trust model and achieves significant performance improvements compared to existing solutions.  

[Download paper here](https://dl.acm.org/doi/abs/10.1145/3642968.3654814)