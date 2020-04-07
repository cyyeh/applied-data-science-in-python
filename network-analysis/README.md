# Applied Social Network Analysis in Python

## Overview

This course will introduce the learner to network analysis through tutorials using the NetworkX library. The course begins with an understanding of what network analysis is and motivations for why we might model phenomena as networks. The second week introduces the concept of connectivity and network robustness. The third week will explore ways of measuring the importance or centrality of a node in a network. The final week will explore the evolution of networks over time and cover models of network generation and the link prediction problem. 

## Key Concepts by Week

Week 1
> Module One introduces you to different types of networks in the real world and why we study them. You'll learn about the basic elements of networks, as well as different types of networks. You'll also learn how to represent and manipulate networked data using the NetworkX library. The assignment will give you an opportunity to use NetworkX to analyze a networked dataset of employees in a small company.

- Recognize and categorize real world networks.
- Identify applications and important questions about networks that network science allows us to answer.
- Determine what type of network is best suited to model real networked data.
- Construct and manipulate networks of different types using different network classes and node and edge attributes in NetworkX.
- Define bipartite graphs and describe related algorithms such as graph projections.
- Manipulate bipartite graphs and related algorithms using NetworkX.

---

Week 2
> In Module Two you'll learn how to analyze the connectivity of a network based on measures of distance, reachability, and redundancy of paths between nodes. In the assignment, you will practice using NetworkX to compute measures of connectivity of a network of email communication among the employees of a mid-size manufacturing company.

- Describe how distance measures can be used to identify central and peripheral nodes in networks and use networkX to identify central and peripheral nodes.
- Define connected components in directed and undirected graphs and use networkX to find them.
- Identify ways of measuring clustering in networks and distinguish the differences in the measures.
- Measure clustering in graphs in NetworkX.
- Identify different types of network attacks and relate them to real world examples.
- Define node and edge connectivity of a network and describe their implication to network robustness.
- Assess how resistant a network is to node and edge removal attacks, using networkX.

---

Week 3
> In Module Three, you'll explore ways of measuring the importance or centrality of a node in a network, using measures such as Degree, Closeness, and Betweenness centrality, Page Rank, and Hubs and Authorities. You'll learn about the assumptions each measure makes, the algorithms we can use to compute them, and the different functions available on NetworkX to measure centrality. In the assignment, you'll practice choosing the most appropriate centrality measure on a real-world setting.

- Identify and define several network centrality measures.
- Describe the differences and similarities between several centrality measures.
- Measure the centrality of nodes in a network using NetworkX.
- Describe how network centrality measures can be used for real world applications.
- Apply centrality analysis to real world networks.

---

Week 4
> In Module Four, you'll explore the evolution of networks over time, including the different models that generate networks with realistic features, such as the Preferential Attachment Model and Small World Networks. You will also explore the link prediction problem, where you will learn useful features that can predict whether a pair of disconnected nodes will be connected in the future. In the assignment, you will be challenged to identify which model generated a given network. Additionally, you will have the opportunity to combine different concepts of the course by predicting the salary, position, and future connections of the employees of a company using their logs of email exchanges.

- Define the degree distribution of a network and use networkX to visualize it.
- Identify the typical properties of real, large networks such as power law like degree distribution, high clustering, and small average shortest paths.
- Describe the mechanics of the Preferential Attachment Model and identify the properties of the networks it generates.
- Describe the mechanics of the Small World Model and identify the properties of the networks it generates.
- Identify and describe several network measures that can be used for link prediction.
- Use NetworkX to create node pair features that are predictive of new edges.
- Use NetworkX to create node features that are predictive of node attributes in a real world setting.