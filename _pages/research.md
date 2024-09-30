---
permalink: /research/
title: "📰 Research Experience"
author_profile: true
redirect_from: 
  - /rs/
  - /research.html
---

I have been fortunate to collaborate with brilliant scientists from McMaster, Rensselaer Polytechnic, California State, Florida State, and Sharif, exploring various fields of machine learning.  
 

📊 Data Centric AI
------
_Under supervision of [Professor Mohammad Mohammadi Amiri](https://mmamiri.github.io/), Rensselaer Polytechnic Institute (Apr-Ongoing 2024)_  

Data is the main fuel of the modern world, enabling AI and driving technological growth. As the demand for data has grown substantially, data products have become valuable assets, essential for sectors seeking high-quality data to discover knowledge. Establishing a principled method to quantify the worth of data and its value for data seekers is crucial. This is addressed through data valuation, which is an essential component for realizing a fair data trading platform for owners and seekers. In this context, data valuation becomes pivotal in marketplaces where buyers seek to enhance their existing datasets by purchasing new data from sellers. The challenge lies in ranking or selecting the datasets offered by sellers without directly exchanging the data itself, thereby preserving privacy and data integrity. Current approaches to data valuation predominantly rely on statistical methods, which often lack scalability and adaptability. I have already contributed to two papers in this area: one focusing on task-agnostic data valuation in graphs and the other on time series datasets.

***[The paper for the graph valuation project is available here](https://arxiv.org/abs/2408.12659).***  
***[The paper for the time series  project is available here](https://ali-falahati.github.io/files/natural.pdf).***  




📇 ML Systems & Blockchain
------
_Under supervision of [Professor Laurent Bindschaedler](https://binds.ch/), Max Planck Institute for Software Systems (Jun-Oct 2023)_  

During my summer internship at Max Planck, I worked on creating a Watcher node, which was a new type of node with the ability to query analytical and complex queries. This addressed a significant unsolved problem in the Ethereum chain. Ethereum clients like Geth traditionally use an OLTP database for storing transactions, which limits their ability to deliver historical information such as the balance of a wallet or the amount of transactions issued from an address within a given time.  

My responsibility was to modify the Geth client and its underlying database to use an OLAP (Online Analytical Processing) database instead. For this project, I utilized the Go programming language. The results were remarkable, with the new approach being 100 times faster than the traditional method of retrieving historical data.  

This improvement in data retrieval speed opened up new possibilities for conducting analytical queries on the Ethereum blockchain, enabling more efficient and effective analysis of transactional data. This project was a significant step towards enhancing the overall functionality and performance of the Ethereum network.

***[The paper for this project is available here](https://dl.acm.org/doi/pdf/10.1145/3642968.3654814).***  

💊 Drug Discovery
------
_Under supervision of [Professor Negin Forouzesh](https://www.calstatela.edu/faculty/negin-forouzesh), California State University (Aug-Dec 2023)_  

Molecular fingerprints are essential cheminformatics tools for machine learning with applications in drug discovery. We develop a novel graph convolutional network (GCN) to predict the binding free energy of protein-ligand complexes. By adding a physics-based layer to the network architecture, the accuracy of the molecular fingerprint has been improved while potential overfitting has been avoided.  

In this project, I had the exciting opportunity to contribute significantly by taking on the responsibility of developing and rigorously testing the PGGCN graph model. The aim was to enhance the overall performance of graph learning. What makes this project even more rewarding is the fact that our model is set to be seamlessly integrated into the esteemed Deepchem (the de facto deep learning library for chemistry) library.  

Throughout the development and testing phase, my focus was on optimizing the performance of the graph model. This involved carefully fine-tuning the various components and parameters, as well as conducting rigorous testing to ensure its accuracy and reliability.  


🌊 Data Science for Climate change
------
_Under supervision of [Professor Nasrin Alamdari](https://www.nasrinalamdari.com/), Florida State University (May-Aug 2022)_  

I joined the Climate Change and Water Resources Research team at Florida State University as their data scientist and machine learning engineer. In this role, I actively participated in multiple projects focused on automating computer software for water resources modeling and applying machine learning techniques to complex natural and man-made systems.  

One of the key objectives of these projects was to identify cost-effective strategies for improving water quality and mitigating floods through the use of multi-objective optimization. Additionally, we worked on predicting harmful algal blooms in freshwater and coastal water by leveraging various watershed and water body variables.  

In addition to modeling and analysis, I also contributed to data visualization efforts and the development of analytical dashboards. I was responsible for setting up databases and pipelines to ensure efficient data management and processing.  

🚦 Big Data for Tehran Traffic
------
_Under supervision of [Professor Iman Gholampour](http://sina.sharif.ir/~imangh/index.html), Sharif University of Technology (Oct-Feb 2022-2023)_  

As part of my Massive Data Analysis course project, I conducted research on implementing and analyzing various big data and machine learning algorithms using __Spark__ and __Hadoop__. Specifically, I focused on algorithms such as Apriori, LSH (Locality-Sensitive Hashing), CF-ALS (Collaborative Filtering with Alternating Least Squares), HITS (Hyperlink-Induced Topic Search), SVD (Singular Value Decomposition), and PIXIE on Tehran Traffic data.  

The main objective of the project was to detect anomaly patterns in the driving behavior of drivers in Tehran using speed control cameras. By analyzing the data from these cameras, we aimed to identify any abnormal driving patterns that may indicate traffic violations or unsafe driving practices.  
Additionally, another aspect of the project involved predicting traffic in different locations throughout the city. By leveraging the collected data and applying machine learning techniques, we aimed to develop models that could accurately forecast traffic conditions in various parts of Tehran. This information would be valuable for traffic management and congestion control purposes.  

Overall, this project provided valuable insights into the application of big data algorithms for traffic analysis and prediction. we aimed to contribute to the development of effective traffic management strategies in Tehran.  

***You can find some notebooks related to this project in this [repository](https://github.com/Mortrest/Tehran-Traffic-Data-Spark)***  
