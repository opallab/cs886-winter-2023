# CS 886: Graph Neural Networks

## Logistics
+ **Instructor:** [Kimon Fountoulakis](https://opallab.ca/team/)
+ **Seminar Room:** TBA
+ **Seminar Time:** Monday and Wednesday 5:30pm-6:50pm

## Overview

Learning from multi-modal datasets is currently one of the most prominent topics in artificial intelligence. The reason behind this trend is that many applications, such as recommendation systems and fraud detection, require the combination of different types of data. In addition, it is often the case that data exhibit relations which need to be captured for downstream applications. In this proposal we are interested in multi-modal data which combine a graph, i.e., a set of nodes and edges, with attributes for each node and/or edge. The attributes of the nodes/edges capture information about the nodes/edges themselves, while the edges among the nodes capture relations among the nodes. Capturing relations is particularly helpful for applications where we are trying to make predictions for nodes given neighborhood data.

One of the most prominent and principled ways of handling such multi-modal data for downstream tasks such as node classification is graph neural networks. Graph neural network models can mix hand-crafted or automatically learned attributes about the nodes while taking into account relational information among the nodes. Therefore, the output vector representation of the graph neural network contains global and local information for the nodes. This contrasts with neural networks that only learn from the attributes of entities. 

This seminar will cover seminal work in the space of graph neural networks For example, spectral and spatial convolutional graph neural networks, graph attention networks, invariant and equivariant graph neural networks, generall message passing graph neural networks. Finally, we will discuss current theoretical understanding of the performance of graph neural networks. For example, what does convolution do to the input data? Does convolution improve generalization compared to not using a graph? How do multiple convolutions change the data and how do they affect generalization?

The seminar is based on weekly paper readings and student presentations, discussions, and
a term project. 

## Schedule
The below schedule is subject to change:
| Week | Date | Topic | Readings |
|:-----|:-----|:-----|:------------|
| 1 | 9/13 | Introduction (Semih lecturing) | <br/> [Geometric Deep Learning](https://arxiv.org/abs/2104.13478) Chapter 1 <br/>|

## Readings

This seminar's reading will cover chapters from the following surveys and textbooks in addition to research papers, which will be posted in the schedule.
+ [Knowledge Representation and Reasoning (KRR)](https://www.cin.ufpe.br/~mtcfa/files/in1122/Knowledge%20Representation%20and%20Reasoning.pdf), Brachman \& Levesque, 2004
+ [Designing and Building Enterprise Knowledge Graphs](https://link.springer.com/book/10.1007/978-3-031-01916-6), Sequeda \& Lassila, 2021
+ [Machine Knowledge: Creation and Curation of Comprehensive Knowledge Bases](https://www.nowpublishers.com/article/Details/DBS-064), Weikum, Dong, Razniewski, Suchanek, 2021
+ [Natural Language Interfaces to Data](https://www.nowpublishers.com/article/Details/DBS-078) Quammar,Efthymiou, Lei, Özcan, 2022
+ [Semantic Web for the Working Ontologist (SWFWO)](https://tinyurl.com/2p9672s2), Allemang \& Hendler, 2008
+ The Protégé Project: [1](https://perso.liris.cnrs.fr/amille/enseignements/MasterCode/IC_IA/session2/protege_evolution.pdf), [2](https://dl.acm.org/doi/pdf/10.1145/2757001.2757003)
+ [Rule-Based Expert Systems: The MYCIN Experiments of the Stanford Heuristic Programming Project](https://people.dbmi.columbia.edu/~ehs7001/Buchanan-Shortliffe-1984/MYCIN%20Book.htm), Buchanan, Shortliffe, 1984
+ [Principles of Database and Knowledge-Base Systems (PDKBS)](https://www.sti-innsbruck.at/sites/default/files/Knowledge-Representation-Search-and-Rules/principles-of-database-and-knowledge-base-systems-volume-1-1.pdf), Ullman, 1989


## Workload Breakdown
+ Class Participation: 15%
+ Paper Reviews: 20%
+ Presentation: 15%
+ Project: 50%

## Paper Reviews
For each seminar (except the first 2 seminars) we will be writing two reviews for two of the papers 
assigned to that day. If there are more than two papers assigned, you can pick any two of 
the assigned papers. You are allowed to skip 1 review throughout the term. I am flexible in the formats of your
review.  The reviews will be 1 pages long (if you need more space take another 0.25 pages but try not to). 
You have to finish your review with 
one question to start a discussion in the seminar. The reviews are due the Monday at 6pm before the seminar. 
You are expected to (very very) briefly answer the following 6 questions and finish your reviews with a
question that can start a discussion in class:

+ What is the problem?
+ Why is it important?
+ Why is it hard? Why don't previous methods work?
+ What is the solution to the problem the authors propose?
+ What interesting research questions does the paper raise?
+ (If related) How does the paper relate to other papers we have read?
The first 4 of these questions are from Jennifer 
Widom's [tips for writing introductions to technical papers](https://cs.stanford.edu/people/widom/paper-writing.html). 
I strongly recommend that each one of you read this entire document 
very carefully (probably multiple times) at some point in your graduate studies. There is no fixed format for the reviews 
but I recommend: Single column, 1.5 space, 12 pt, in Latex.

Ultimately, the main thing I am looking for is a demonstration of serious critical reading of the paper.

## Project Deliverables
There are two main deliverables of your project, a 6-page paper and the source code of your project 
with instructions to run your code.
+ Project Paper: The project papers will be 6 pages. You can have extra pages for the references.
They will be written in the two-column ACM proceedings format, using one of the ACM SIG Proceedings Templates.
+ Project Source Code: Please put your source code into github and include a link in your project writeup. 
On the github page, please document exactly how to run your source code.


## Presentations
Each student will be doing 1 presentation in the term. Each presentation will be about 25 minutes long. 
Here are the important points summarizing what you have to do for your presentations.

+ You must present with slides. The content in your slides should be your own but you can use others' materials, e.g., 
figures from the paper we are reading, when necessary and by crediting your source on your slide.
+ Please have a separate slide for each of 4 questions in the summary item in the Paper Review section.
+ It is very helpful to demonstrate the ideas in the paper through examples. So try to have examples in your presentation, e.g., a simulation of some code or system component.
