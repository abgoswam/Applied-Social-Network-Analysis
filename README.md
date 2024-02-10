# Applied-Social-Network-Analysis

## Introduction

This project involves analyzing social networks using the `networkx` library in Python. Multiple assignments are included, each focusing on different aspects of social network analysis. The assignments deal with creating and manipulating graphs, exploring bipartite graphs, and analyzing email communication networks within a company.

## Dependencies

- `networkx`
- `pandas`
- `numpy`
- `matplotlib`

Install the dependencies using:

```bash
pip install networkx pandas numpy matplotlib

```

# Table of Contents

1. [Assignment 1](#assignment-1)
   1.1 [Introduction](#introduction)
   1.2 [Functions](#functions)
   1.3 [How to Run](#how-to-run)

2. [Assignment 2](#assignment-2)
   2.1 [Introduction](#introduction-1)
   2.2 [Functions](#functions-1)
   2.3 [How to Run](#how-to-run-1)

3. [Assignment 3](#assignment-3)
   3.1 [Introduction](#introduction-2)
   3.2 [Functions](#functions-2)
   3.3 [How to Run](#how-to-run-2)

4. [Assignment 4](#assignment-4)
   4.1 [Introduction](#introduction-3)
   4.2 [Functions](#functions-3)
   4.3 [How to Run](#how-to-run-3)

5. [Acknowledgments](#acknowledgments)

6. [License](#license)

7. [External Resources](#external-resources)

8. [Troubleshooting](#troubleshooting)

9. [Feedback and Contribution](#feedback-and-contribution)

---

## Assignment 1

### Introduction

The first assignment focuses on creating and manipulating graphs based on employee movie choices and relationships. The analysis involves loading bipartite graphs, adding node attributes, finding weighted projections, and exploring relationships between movie preferences and employee interactions.

### Functions

- `answer_one()`: Load bipartite graph from `Employee_Movie_Choices.txt`.
- `answer_two()`: Add node attributes for movies and employees to the graph.
- `answer_three()`: Find a weighted projection of the graph to determine common movie preferences.
- `answer_four()`: Calculate the Pearson correlation between employee relationship scores and the number of common movies.

### How to Run

Run each function in a Python environment or Jupyter notebook. View the results and analysis for each question.

## Assignment 2

### Introduction

The second assignment involves analyzing an internal email communication network between employees of a mid-sized manufacturing company. The analysis includes loading a directed multigraph, determining connectivity aspects, finding strongly connected components, and extracting insights from the network.

### Functions

- `answer_one()`: Load directed multigraph from `email_network.txt`.
- `answer_two()`: Determine the number of employees and emails represented in the graph.
- `answer_three()`: Determine if information can flow from every employee to every other employee based on email communication.
- `answer_four()`: Find the number of nodes in the largest weakly connected component.
- `answer_five()`: Find the number of nodes in the largest strongly connected component.
- `answer_six()`: Find the subgraph of nodes in the largest strongly connected component.
- `answer_seven()`: Determine the average distance between nodes in the subgraph.
- `answer_eight()`: Determine the largest possible distance between two employees in the subgraph.
- `answer_nine()`: Find the set of nodes with eccentricity equal to the diameter in the subgraph.
- `answer_ten()`: Find the set of nodes with eccentricity equal to the radius in the subgraph.
- `answer_eleven()`: Find the node connected to the most other nodes by a shortest path of length equal to the diameter.
- `answer_twelve()`: Determine the smallest number of nodes to remove to prevent communication to a specific node.

### How to Run

Run each function in a Python environment or Jupyter notebook. View the results and analysis for each question.

## Assignment 3

### Introduction

The third assignment focuses on analyzing a real-world social network - the Facebook network of a small American college. The analysis involves loading and exploring the network, calculating various centrality measures, and identifying influential nodes.

### Functions

- `answer_one()`: Load the Facebook network from `facebook_combined.txt`.
- `answer_two()`: Visualize the Facebook network.
- `answer_three()`: Calculate various centrality measures.
- `answer_four()`: Identify the most central node based on degree centrality, closeness centrality, and betweenness centrality.

### How to Run

Run each function in a Python environment or Jupyter notebook. View the results and analysis for each question.

## Assignment 4

### Introduction

The fourth assignment involves analyzing a collaboration network of scientists who have published papers on network science. The analysis includes loading and exploring the network, calculating various centrality measures, and identifying influential nodes.

### Functions

- `answer_one()`: Load the collaboration network from `ca-GrQc.txt`.
- `answer_two()`: Visualize the collaboration network.
- `answer_three()`: Calculate various centrality measures.
- `answer_four()`: Identify the most central node based on degree centrality, closeness centrality, and betweenness centrality.

### How to Run

Run each function in a Python environment or Jupyter notebook. View the results and analysis for each question.

## Acknowledgments

These assignments are part of the "Python for Social Network Analysis" course on Coursera. Special thanks to the course instructors and contributors.

## External Resources

- [NetworkX Documentation](https://networkx.github.io/documentation/stable/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)


## Feedback and Contribution

Feel free to provide feedback or contribute to the project. Report issues, suggest improvements, or contribute to the codebase.
