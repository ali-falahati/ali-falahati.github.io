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
I am generally curious about the intersection of Machine Learning with Social Sciences. My main areas of interests include:

- Graph Neural Networks
- Computational Social Science
- Health Care AI
- Deep Learning


  

📰 Research Experience
======

Graph Neural Networks
------

My Bsc thesis is on “__OGRE: Online Anomaly Detection using Generative Graph Neural Networks__”.  
__OGRE__ is a project that focuses on online anomaly detection using Generative Graph Neural Networks. After a successful summer at the Max Planck Institute, we have decided to extend our project. Our new project is a direct result of our previous work, which introduced the concept of Watcher nodes.  

In traditional fintech products like Paypal, fraudulent activities are detected before they occur and then sent for further inspection. However, in the blockchain space, we can only track fraudulent activities and there are no mechanisms in place to prevent them from happening. Before the introduction of Watcher nodes, online anomaly detection in blockchain seemed infeasible due to factors such as the lack of access to historical events in a reasonable time. With the introduction of Watcher nodes, each node can retrieve historical data regarding a wallet address or contract much faster than the current method.  

OGRE leverages both the structural and feature-based anomalies of the graphs. The project is designed to perform anomaly detection in three stages.  

> - Featurization: Using Watcher nodes, historical features such as volume and number of transactions are extracted.
> - Cherry-picking nodes: The model now selects relevant nodes from both the sender and receiver using random sampling and a relevant embedding space.
> - Generating various-sized graphs: With the selected nodes, graphs ranging in size from 5 to 12 are generated and scored based on the entire graph structure. These scores are then aggregated to determine if a specific transaction is suspicious or not.  

Drug Discovery
------
Molecular fingerprints are essential cheminformatics tools for machine learning with applications in drug discovery. We develop a novel graph convolutional network (GCN) to predict the binding free energy of protein-ligand complexes. By adding a physics-based layer to the network architecture, the accuracy of the molecular fingerprint has been improved while potential overfitting has been avoided.  

In this project, I had the exciting opportunity to contribute significantly by taking on the responsibility of developing and rigorously testing the PGGCN graph model. The aim was to enhance the overall performance of graph learning. What makes this project even more rewarding is the fact that our model is set to be seamlessly integrated into the esteemed Deepchem (the de facto deep learning library for chemistry) library.  

Throughout the development and testing phase, my focus was on optimizing the performance of the graph model. This involved carefully fine-tuning the various components and parameters, as well as conducting rigorous testing to ensure its accuracy and reliability.  

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
