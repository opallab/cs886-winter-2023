# Graph Neural Networks

## Logistics
+ **Instructor:** [Semih Salihoglu](https://cs.uwaterloo.ca/~ssalihog/)
+ **Seminar Room:** DC 2585
+ **Seminar Time:** Tue 4pm-6:50pm

## Overview
The quest to build intelligent machines that are capable of logical reasoning, i.e., ones that can 
induce new information  or deduce logical rules from prior information, is as old as the field of 
computer science. Research topics motivated with this ultimate goal is at the heart of 
symbolic (as opposed to statistical) artificial intelligence and connects with many sub-fields 
of computer science, such as data management and semantic web, as well as other scientific fields,
such as linguistics. These systems are generally based on forming a knowledge base or 
knowledge graph that represent a set of facts about a real world application domain,
as well as elementary logical rules specifying constraints about the domain, as well
as an inference system that can answer questions using the base facts and the rules.
Historically, there has been several periods that have popularized the development of such 
knowledge graph-based applications. The strongest of these have been the expert systems of 1980,
the semantic web of 2000s, and the current wave of question answering in search engines, 
recommender systems, and dataset cataloging/search for extremely heterogeneous 
large public goverment and private enterprise data lakes.

This seminar will cover seminal work in the space of knowledge graph representation, querying,
management, and past and primarily modern applications that are powered by knowledge graphs.
Topics include knowledge models, ontologies, query languages, graph data management systems,
public knowledge graphs, knowledge graph embeddings, popular successful past and present
applications. 

The seminar is based on weekly paper readings and student presentations, discussions, and
a term project. 

## Schedule
The below schedule is subject to change:
| Week | Date | Topic | Readings |
|:-----|:-----|:-----|:------------|
| 1 | 9/13 | Introduction (Semih lecturing) |  [Knowledge Graphs](https://dl.acm.org/doi/10.1145/3418294) <br/> [The Semantic Web](https://www.jstor.org/stable/26059207?seq=1#metadata_info_tab_contents) <br/> SWFO Ch 3, 5-7|
| 2 | 9/20 | Guest Lecture: Prof. Grant Weddell  <br/> Foundations of Knowledge Representation | KRR Ch 2 & 3 <br/> (No reviews but do Exercises 1 and 4 in Ch 2.7 of KRR and submit a pdf (latex or hand written)). |
| 3 | 9/27 | Datalog (Semih lecturing online) |  PDKBS 3 (from pgs 96 to 139 but I highly recommend 139-164 <br /> as well if you have not read on the formalism of relational algebra) |
| 4 | 10/04   | Query Processing in Deductive DBMS: Magic Sets (Semih lecturing) | PDKBS 12.1-12.8, PDKBS 13.1-13.5 <br/> Optional: [Magic Sets Original Paper](https://dl.acm.org/doi/10.1145/6012.15399) <br/> Optional: [Magic is Relevant](https://dl.acm.org/doi/abs/10.1145/93605.98734) |
| -- | 10/11   | No Class (Reading Week) | |
| 5 | 10/18   | RDF Systems | [RDFox](https://link.springer.com/content/pdf/10.1007/978-3-319-25010-6_1.pdf) <br/> [RDF3x](https://dl.acm.org/doi/10.14778/1453856.1453927) |
| 6 | 10/25   | Property Graph Data Management Systems (Semih and Amine lecturing) | [The Ubiquity of Large Graphs User Survey](https://cs.uwaterloo.ca/~jimmylin/publications/Sahu_etal_VLDBJ2019.pdf) <br/> [FDB](http://vldb.org/pvldb/vol5/p1232_nurzhanbakibayev_vldb2012.pdf) <br/> [Optimizing Subgraph Queries by Combining Binary and WCOJ](https://www.vldb.org/pvldb/vol12/p1692-mhedhbi.pdf) <br/> Optional: [Umbra WCOJ Implementation](https://db.in.tum.de/~freitag/papers/p1891-freitag.pdf) |
| 7 | 11/01   | Large Public Knowledge Graphs and Ontologies | [DBPedia](https://www.researchgate.net/publication/259828897_DBpedia_-_A_Large-scale_Multilingual_Knowledge_Base_Extracted_from_Wikipedia) <br/> [SNODEM](https://link.springer.com/book/10.1007/978-981-287-895-3): Ch 3, Ch 4.1-4.3.8.3, 4.4 <br/> [Schema.org](https://queue.acm.org/detail.cfm?id=2857276) |
| 8 | 11/08   | Enterprise Knowledge Graphs & Management Systems | [Sequeda Thesis Ch 3](https://repositories.lib.utexas.edu/bitstream/handle/2152/30537/SEQUEDA-DISSERTATION-2015.pdf) <br/> [Sequeda Thesis Ch 4](https://repositories.lib.utexas.edu/bitstream/handle/2152/30537/SEQUEDA-DISSERTATION-2015.pdf) <br/> [Optional: Pay-as-you-go Methodology Case Study](https://github.com/juansequeda/papers/blob/master/iswc2019.pdf) (Focus on Section 4)|
| 9 | 11/15   | Natural Language Interfaces to Data | [BELA](https://download.hrz.tu-darmstadt.de/pub/FB20/Dekanat/Publikationen/UKP/76500354.pdf) <br/> [ATHENA](http://www.vldb.org/pvldb/vol9/p1209-saha.pdf) <br/> [Optional: ATHENA++](http://www.vldb.org/pvldb/vol13/p2747-sen.pdf) <br/> [Optional: IRNet](https://aclanthology.org/P19-1444.pdf)|
| 10 | 11/22   | Graph Embeddings/Deep Natural Language Embeddings  | [TransE](https://proceedings.neurips.cc/paper/2013/file/1cecc7a77928ca8133fa24680a88d2f9-Paper.pdf) <br/> [Q&A With Embeddings](https://arxiv.org/pdf/1406.3676.pdf) <br/> [Optional: Survey on KG Embeddings](https://ieeexplore.ieee.org/document/8047276)|
| 11 | 11/29   |  Guest Lecture on Data Cataloging: Juan Sequeda & Other Enterprise Applications | [Datanami Article](https://www.datanami.com/2022/09/30/what-does-it-mean-for-a-data-catalog-to-be-powered-by-a-knowledge-graph/) <br/> [Saga](https://arxiv.org/pdf/2204.07309.pdf) |
| 12 | 12/06   | Linked Open Data Movement | [Google Dataset Search](https://dl.acm.org/doi/pdf/10.1145/3308558.3313685) <br/> [Table Union Search](http://www.vldb.org/pvldb/vol11/p813-nargesian.pdf) <br/> Optional: [Making Open Datasets Transparent](http://www.cs.toronto.edu/~christina/documents/MakingOpenDataTransparent.pdf)|

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
