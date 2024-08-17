# Graph Analysis and Link Prediction with Node Embeddings

## Overview

This project focuses on analyzing a graph dataset and predicting potential connections between nodes. The key tasks include graph analysis, node embedding, and link prediction. The primary goals are to understand the structure of the graph, generate meaningful node embeddings, and apply machine learning algorithms to predict links between nodes.

## Main Tasks

1. **Graph Analysis:**
   - Analyze the graph to identify key properties and characteristics, such as centrality measures, clustering coefficients, and assortativity.
   - Identify influential nodes within the graph to understand the network structure.

2. **Node Embedding:**
   - Utilize the Node2Vec approach to generate node embeddings.
   - Perform random walks on the graph to capture contextual relationships between nodes and train a Word2Vec model for embedding generation.

3. **Link Prediction:**
   - Implement and evaluate machine learning algorithms for link prediction using the generated node embeddings.
   - Compare different binary operators for combining node embeddings to predict links.
   - Train and assess models such as Logistic Regression and Random Forest classifiers to determine the most effective link prediction strategy.

4. **Evaluation:**
   - Compare the performance of machine learning models against a baseline to evaluate their effectiveness.
   - Analyze and interpret the results to determine the best-performing models and prediction strategies.

## Jupyter Notebook

The detailed implementation, including code, results, and analyses, is provided in the Jupyter Notebook file. This file contains the specific steps, visualizations, and interpretations of the results for each task.

## Conclusion

This project aims to leverage graph analysis and node embedding techniques to enhance link prediction tasks. By analyzing the graph structure and applying machine learning models, the project provides insights into potential future connections and network dynamics.

## How to Run

1. **Install Dependencies:**
   Make sure to install the required libraries and packages. 

2. **Data Acquisition**:
   - The dataset used for this analysis was obtained from the [Network Repository](https://networkrepository.com/index.php), an interactive data and network data repository with real-time visual analytics.
   - [Click to access the web page where the data is provided](https://networkrepository.com/fb-pages-tvshow.php).

3. **Data Preparation:**
   Prepare the graph data and ensure it is in the required format for analysis and embedding.

4. **Run Analysis:**
   Execute the Jupyter Notebook provided to perform graph analysis, node embedding, and link prediction. The notebook includes detailed steps and code for each task.

5. **Review Results:**
   Check the results and performance metrics presented in the Jupyter Notebook to understand the outcomes of the analysis and prediction tasks.

