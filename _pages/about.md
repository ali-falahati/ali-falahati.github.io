---
permalink: /
title: "👋 Hello, there, I'm Ali"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---  

![networks](/images/felan.jpg){: .align-right width="280px"}
I’m a bachelor student studying Computer Science at **Sharif University of Technology**.  
  

I am currently a scientific intern at **Max Planck Institute for Software Systems**, Germany where I have the great pleasure to work with [Professor Laurent Bindschaedler](https://binds.ch/) on Graph anomaly detection and blockchain.    

Prior to that, I worked on drug discovery using GNN under the supervision of [Professor Negin Forouzesh](https://www.calstatela.edu/faculty/negin-forouzesh) at **California State University**.


  

📌 Research Interests 
======
 My main areas of interests include:  

- __Graph Neural Networks__
- __Computational Social Science__
- __Health Care AI__
- __Deep Learning__

I have always been deeply intrigued by the fascinating overlap between the field of Machine Learning and its applications in the realms of Social Sciences and Health care.  

To get a comprehensive understanding of my [Research](https://ali-falahati.github.io/research/) and [Work](https://ali-falahati.github.io/work/) experiences, as well as my [Projects](https://ali-falahati.github.io/pj/), please take a look at my detailed descriptions.  

Besides my professional pursuits, I have a deep passion for reading. I consider myself a true bookworm and find joy in immersing myself in books, expanding my knowledge, and exploring different worlds through literature. Reading is not only a hobby for me, but also a way to relax, learn, and broaden my perspective. You can view some of my favorite books in the [Misc.](https://ali-falahati.github.io/misc/) tab.  
In addition to books, I also enjoy listening to podcasts and practicing daily meditation.

<!-- 📰 Research Experiences
======
I have been fortunate to collaborate with brilliant scientists from MPI, Cal State, FSU, and SUT, exploring various fields of machine learning.  
 

👹 Graph Neural Networks
------
_Under supervision of professor Laurent Bindschaedler, Max Planck Institute for Software Systems (Sep-Ongoing 2023)_  

My Bsc thesis is on “__OGRE: Online Anomaly Detection using Generative Graph Neural Networks__”.  

__OGRE__ is a project that focuses on online anomaly detection using Generative Graph Neural Networks. After a successful summer at the Max Planck Institute, we have decided to extend our project. Our new project is a direct result of our previous work, which introduced the concept of Watcher nodes.  

In traditional fintech products like Paypal, fraudulent activities are detected before they occur and then sent for further inspection. However, in the blockchain space, we can only track fraudulent activities and there are no mechanisms in place to prevent them from happening. Before the introduction of Watcher nodes, online anomaly detection in blockchain seemed infeasible due to factors such as the lack of access to historical events in a reasonable time. With the introduction of Watcher nodes, each node can retrieve historical data regarding a wallet address or contract much faster than the current method.  

OGRE leverages both the structural and feature-based anomalies of the graphs. The project is designed to perform anomaly detection in three stages.  

> - Featurization: Using Watcher nodes, historical features such as volume and number of transactions are extracted.
> - Cherry-picking nodes: The model now selects relevant nodes from both the sender and receiver using random sampling and a relevant embedding space.
> - Generating various-sized graphs: With the selected nodes, graphs ranging in size from 5 to 12 are generated and scored based on the entire graph structure. These scores are then aggregated to determine if a specific transaction is suspicious or not.  

💊 Drug Discovery
------
_Under supervision of [Professor Negin Forouzesh](https://www.calstatela.edu/faculty/negin-forouzesh), California State University (Aug-Ongoing 2023)_  

Molecular fingerprints are essential cheminformatics tools for machine learning with applications in drug discovery. We develop a novel graph convolutional network (GCN) to predict the binding free energy of protein-ligand complexes. By adding a physics-based layer to the network architecture, the accuracy of the molecular fingerprint has been improved while potential overfitting has been avoided.  

In this project, I had the exciting opportunity to contribute significantly by taking on the responsibility of developing and rigorously testing the PGGCN graph model. The aim was to enhance the overall performance of graph learning. What makes this project even more rewarding is the fact that our model is set to be seamlessly integrated into the esteemed Deepchem (the de facto deep learning library for chemistry) library.  

Throughout the development and testing phase, my focus was on optimizing the performance of the graph model. This involved carefully fine-tuning the various components and parameters, as well as conducting rigorous testing to ensure its accuracy and reliability.  

📇 ML Systems & Blockchain
------
_Under supervision of [Professor Laurent Bindschaedler](https://binds.ch/), Max Planck Institute for Software Systems (Jun-Oct 2023)_  

During my summer internship at Max Planck, I worked on creating a Watcher node, which was a new type of node with the ability to query analytical and complex queries. This addressed a significant unsolved problem in the Ethereum chain. Ethereum clients like Geth traditionally use an OLTP database for storing transactions, which limits their ability to deliver historical information such as the balance of a wallet or the amount of transactions issued from an address within a given time.  

My responsibility was to modify the Geth client and its underlying database to use an OLAP (Online Analytical Processing) database instead. For this project, I utilized the Go programming language. The results were remarkable, with the new approach being 100 times faster than the traditional method of retrieving historical data.  

This improvement in data retrieval speed opened up new possibilities for conducting analytical queries on the Ethereum blockchain, enabling more efficient and effective analysis of transactional data. This project was a significant step towards enhancing the overall functionality and performance of the Ethereum network.

***The paper for this project is currently in progress and is scheduled to be submitted by November.***  

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

***You can find some notebooks related to this project in this [repository](http://sina.sharif.ir/~imangh/index.html)***  


🏢 Work Experiences
======  

📦 Co-Founder of Kargo
------
_Full-time, Tehran, Iran (Dec-Feb 2021-2023)_  

I co-founded Kargo, a startup that aimed to become the first group-lancing platform for AI and data science projects. Our goal was to connect companies looking to outsource their AI projects, such as business analytics, churn prediction, sales forecasting, and data management jobs like setting up data warehouses and pipelines, with skilled freelancers in our network.  

At Kargo, I took on the responsibility of making contracts with companies that needed AI expertise. We ensured that we fully understood their project requirements and objectives. Once the contracts were established, we distributed the projects to our in-house freelancers who had the relevant skills and expertise.  

Our platform provided a seamless experience for both companies and freelancers. We facilitated the entire project lifecycle, from scoping and planning to execution and delivery.   

***Kargo was acquired by Hermes Capital.***


📈 Data Scientist at Hermes Capital
------
Hermes Capital is a prominent fintech company based in Tehran, Iran, dedicated to revolutionizing the Iranian Stock Market and Cryptocurrency Market through its expertise in Algorithmic Trading and Machine Learning approaches.  

As a Data Scientist at Hermes Capital, my role involved extensive research and exploration of Reinforcement Learning Algorithms, with a specific focus on Deep Q-Network (DQN) algorithms. I successfully developed a robust and efficient infrastructure for algorithmic trading using Python, leveraging the power of Machine Learning to analyze market data and make data-driven investment decisions.   -->






