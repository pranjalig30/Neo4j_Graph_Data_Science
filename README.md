# Relation Prediction Using Neo4j - Graph Data Science Library
Machine Learning using Neo4j

Implemented graph data science techniques to forecast actor collaborations with 81% accuracy in a large Netflix dataset. 
Utilized the Cypher Query and Random Forest algorithms.

* **Objective**: use graph features to predict future collaboration between actors based on previous collaboration.
* The last section presents the importance of each of the features used on the prediction performance.
* The graph parameters used are: Common neighbors, preferential attachment, total neighbors, triangles count, clustering coefficient, Louvain coefficient, and partition community detection.

Note: this paper is based on the notebook ‘Analyze netflix data using graphs (neo4j) published by [Yann Claudel.](https://www.kaggle.com/code/yclaudel/analyze-netflix-data-using-graphs-neo4j)

## Fun Read

[Everything You Need to Know About Graph Databases (Neo4j)](https://towardsdatascience.com/everything-you-need-to-know-about-graph-databases-neo4j-b9154f57dad0)

For this project, I am utilizing the Neo4j desktop version and running the sandbox on my local browser.
Steps to connect Neo4j Desktop with Jupyter Notebook:

1. Launch the Neo4j Desktop application.
2. Create a new project by clicking the "+ New" button.
3. Within the project, create a new Graph DBMS by clicking the "+ Add" button.
4. Choose the 'Local DBMS' option from the menu.
5. During the creation of the Graph DBMS, set a password and ensure you record it for future use.
6. This notebook utilizes Neo4j version 5.3.0.
7. After creating the Graph DBMS, click it to open the options toolbar on the right-hand side, then select the "Plugins" option and install the APOC and Graph Data Science Library.
8. Next, click on the three dots next to the "Open" button and choose "Settings."
9. Scroll to the bottom of the text file and set the `memory.heap.max_size` to 6G.

The Neo4j Graph Data Science (GDS) library provides efficiently implemented, parallel versions of common graph algorithms, exposed as Cypher procedures. Additionally, GDS includes machine learning pipelines to train predictive supervised models to solve graph problems, such as predicting missing relationships.
By leveraging the Graph Data Science Library and APOC (Awesome Procedures on Cypher), our approach is to analyze the intricate relationships and connections present within the movie industry. 

Through the fusion of graph theory, data science, and advanced querying capabilities, we aim to provide insights into the likelihood of future collaborations between actors, offering valuable strategic information to stakeholders in the entertainment industry.
