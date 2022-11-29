# CS 886: Graph Neural Networks

## Logistics
+ **Instructor:** [Kimon Fountoulakis](https://opallab.ca/team/)
+ **Seminar Room:** TBA
+ **Seminar Time:** Monday and Wednesday 5:30pm-6:50pm

## Overview

Learning from multi-modal datasets is currently one of the most prominent topics in artificial intelligence. The reason behind this trend is that many applications, such as recommendation systems and fraud detection, require the combination of different types of data. In addition, it is often the case that data exhibit relations which need to be captured for downstream applications. In this proposal we are interested in multi-modal data which combine a graph, i.e., a set of nodes and edges, with attributes for each node and/or edge. The attributes of the nodes/edges capture information about the nodes/edges themselves, while the edges among the nodes capture relations among the nodes. Capturing relations is particularly helpful for applications where we are trying to make predictions for nodes given neighborhood data.

One of the most prominent and principled ways of handling such multi-modal data for downstream tasks such as node classification is graph neural networks. Graph neural network models can mix hand-crafted or automatically learned attributes about the nodes while taking into account relational information among the nodes. Therefore, the output vector representation of the graph neural network contains global and local information for the nodes. This contrasts with neural networks that only learn from the attributes of entities. 

This seminar will cover seminal work in the space of graph neural networks. For example, spectral and spatial convolutional graph neural networks, graph attention networks, invariant and equivariant graph neural networks, generall message passing graph neural networks. We will focus on both practical and theoretical aspects of graph neural networks. Practical aspects include, scalability and performance on real data. Examples of theoretical questions include: what does convolution do to the input data? Does convolution improve generalization compared to not using a graph? How do multiple convolutions change the data and how do they affect generalization?

The seminar is based on weekly paper readings and student presentations, discussions, and
a term project. 

## (Tentative) Schedule
The below schedule is subject to change:
| Week | Date | Topic | Readings |
|:-----|:-----|:-----|:------------|
| 1 | 1/9 | Introduction, problems and applications (Kimon lecturing) | [Geometric Deep Learning](https://arxiv.org/abs/2104.13478) (Chapter 1) <br/> [Geometric foundations of Deep Learning](https://towardsdatascience.com/towards-geometric-deep-learning-iv-chemical-precursors-of-gnns-11273d74125) <br/>  [Towards Geometric Deep Learning I: On the Shoulders of Giants](https://towardsdatascience.com/towards-geometric-deep-learning-i-on-the-shoulders-of-giants-726c205860f5) <br/> [Towards Geometric Deep Learning II: The Perceptron Affair](https://towardsdatascience.com/towards-geometric-deep-learning-ii-the-perceptron-affair-fafa61b5c40a) <br/> [Towards Geometric Deep Learning III: First Geometric Architectures](https://towardsdatascience.com/towards-geometric-deep-learning-iii-first-geometric-architectures-d1578f4ade1f) <br/> [A Gentle Introduction to Graph Neural Networks](https://distill.pub/2021/gnn-intro/) <br/> [Intro to graph neural networks (ML Tech Talks)](https://www.youtube.com/watch?v=8owQBFAHw7E) <br/> [Foundations of Graph Neural Networks](https://www.youtube.com/watch?v=uF53xsT7mjc)|
| 1 | 1/11 | Spatial graph convolution and its theoretical performance on simple random data (Kimon lecturing) | [Semi-Supervised Classification with Graph Convolutional Networks](https://arxiv.org/abs/1609.02907) <br/> [Semi-Supervised Classification with Graph Convolutional Networks](https://proceedings.mlr.press/v139/baranwal21a.html), [Video](https://zoom.us/rec/play/X1FbBJiP1bLTixjmU7wBw233sutk939XulBkrY0Szes9KSNh_cFovdohKoZ-KXFaCZJ5G5yg4m5nKZol.47Ol60UmzMVLZec8?startTime=1624287370000&_x_zm_rtaid=2ArAs6KUSwiFwnA5V61cmQ.1624792221031.e0fb3030146eeed7cee824bfc92e70b5&_x_zm_rhtaid=77) (time 1:03:34) <br/> [PyTorch code for GCN](https://pytorch-geometric.readthedocs.io/en/latest/modules/nn.html#torch_geometric.nn.conv.GCNConv), [Example code](https://pytorch-geometric.readthedocs.io/en/latest/notes/introduction.html) | 
| 2 | 1/16 | Multilayer graph convolution network and its theoretical performance on simple random data (Kimon lecturing) | [Effects of Graph Convolutions in Multi-layer Networks](https://arxiv.org/abs/2204.09297), [Code for reproducing the experiments](https://github.com/opallab/Effects-of-Graph-Convs-in-Deep-Nets) <br/> [Theory of Graph Neural Networks: Representation and Learning](https://arxiv.org/abs/2204.07697) | 
| 2 | 1/18 | Graph Attention Network and Graph Attention Retrospective (Kimon lecturing) | [Graph Attention Networks](https://arxiv.org/abs/1710.10903), [PyTorch Code](https://pytorch-geometric.readthedocs.io/en/latest/modules/nn.html#torch_geometric.nn.conv.GATConv) <br/> [Graph Attention Retrospective](https://arxiv.org/abs/2202.13060), [Code for reproducing the experiments](https://github.com/opallab/Graph-Attention-Retrospective/), [Video lecture](https://youtu.be/duWVNO8_sDM) <br/> [Theory of Graph Neural Networks: Representation and Learning](https://arxiv.org/abs/2204.07697) | 
| 3 | 1/23 | ΤΒΑ |  | 



## Readings (to be updated)

+ [Geometric Deep Learning](https://geometricdeeplearning.com), Michael M. Bronstein, Joan Bruna, Taco Cohen, Petar Veličković, 2021
+ [Theory of Graph Neural Networks: Representation and Learning](https://arxiv.org/abs/2204.07697), Stefanie Jegelka, 2022
+ [Graph Representation Learning Book](https://www.cs.mcgill.ca/~wlh/grl_book/), William L. Hamilton, 2020
+ [Graph Neural Networks](https://graph-neural-networks.github.io), Lingfei Wu, Peng Cui, Jian Pei, Liang Zhao, (2022)
+ [High Dimensional Probability](https://www.math.uci.edu/~rvershyn/papers/HDP-book/HDP-book.pdf), Roman Vershynin, 2022

## Other courses online related to machine learning on graphs

+ [Machine Learning with Graphs](https://web.stanford.edu/class/cs224w/), Jure Leskovec, Stanford
+ [Graph Representation Learning](https://cs.mcgill.ca/~wlh/comp766/), William L. Hamilton, McGill
+ [Introduction to Graph Neural Networks](https://www.youtube.com/watch?v=Iiv9R6BjxHM), Xavier Bresson, Nanyang Techinical University and NYU
+ [Recent Developments in Graph Network Architectures](https://www.youtube.com/watch?v=M60huxIvKbE), Xavier Bresson, Nanyang Techinical University
+ [Benchmarking GNNs](https://www.youtube.com/watch?v=tuChBSo8_eg), Xavier Bresson, Nanyang Techinical University
+ [Foundations of Graph Neural Networks](https://www.youtube.com/watch?v=uF53xsT7mjc), Petar Veličković, DeepMind
+ [Geometric Deep Learning Course](https://geometricdeeplearning.com/lectures/)
+ [Machine Learning for the Working Mathematician: Geometric Deep Learning](https://www.youtube.com/watch?v=7pRIjJ_u2_c), Geordie Williamson, The University of Syndney
+ [Advanced lectures on community detection](https://indico.ictp.it/event/9797/other-view?view=ictptimetable), Laurent Massoulie, INRIA Paris

## Code

+ [PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/)
+ [Deep Graph Library](https://www.dgl.ai)

## Competitions

+ [Open Graph Benchmark](https://ogb.stanford.edu/docs/leader_overview/)

## Datasets

+ [PyTorch Geometric Datasets](https://pytorch-geometric.readthedocs.io/en/latest/modules/datasets.html)
+ [Open Graph Benchmark](https://ogb.stanford.edu)
+ [HyperGraphs](https://www.cs.cornell.edu/~arb/data/)
+ [TUDatasets](https://chrsmrrs.github.io/datasets/)
+ [Non Homophily Benchmarks](https://github.com/CUAI/Non-Homophily-Benchmarks)
+ [Graph Learning Benchmarks](https://graph-learning-benchmarks.github.io/glb2022)
+ [Hetionet](https://het.io)
+ [Heterogeneous graph benchmarks](https://www.biendata.xyz/hgb/)
+ [Long Range Graph Benchmark](https://towardsdatascience.com/lrgb-long-range-graph-benchmark-909a6818f02c)


## Workload Breakdown
+ Class Participation: 15%
+ Paper Reviews: 20%
+ Presentation: 15%
+ Project: 50%

## Paper Reviews
For each seminar (except the first 4 seminars) we will be writing one review for one of the papers 
assigned to that day. If there are more than one papers assigned, you can pick any of 
the assigned papers. You are allowed to skip 2 review throughout the term. I am flexible in the formats of your
review.  The reviews will be 1 page long (if you need more space take another 0.25 page but try not to). 
You have to finish your review with one question to start a discussion in the seminar. The reviews are due at 12pm Monday for the Monday seminar and at 12pm on Wednseday for the Wednsday seminar. 
You are expected to (very very) briefly answer the following 6 questions and finish your reviews with a
question that can start a discussion in class:

+ What is the problem?
+ Why is it important?
+ Why don't previous methods work on that problem?
+ What is the solution to the problem the authors propose?
+ What interesting research questions does the paper raise?

There is no fixed format for the reviews but I recommend: Single column, 1.5 space, 12 pt, in Latex.
Ultimately, the main thing I am looking for is a demonstration of serious critical reading of the paper.

## Project Deliverables
There is one main deliverable of your project, a 6-page paper and (if relevant) the source code of your project 
with instructions to run your code.
+ Project Paper: The project papers will be 6 pages. You can have extra pages for the references and the appendix.
They will be written in the two-column [ICML](https://icml.cc) format, using the ICML template which you can find in the corresponding website.
+ Project Source Code: Please put your source code into github and include a link in your project writeup. 
On the github page, please document exactly how to run your source code.


## Presentations
Each student will be doing at least 1 presentation in the term. Each presentation will be about 25 minutes long. 
Here are the important points summarizing what you have to do for your presentations.

+ You must present with slides. The content in your slides should be your own but you can use others' materials, e.g., 
figures from the paper we are reading, when necessary and by crediting your source on your slide.
+ Please have a separate slide for each of 4 questions in the summary item in the Paper Review section.
+ It is very helpful to demonstrate the ideas in the paper through examples. So try to have examples in your presentation.
