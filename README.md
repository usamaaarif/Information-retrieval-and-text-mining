# Information Retrieval Assignment

This project is a Jupyter Notebook implementation of various Information Retrieval (IR) techniques. It demonstrates the process of building a search engine component, starting from data preprocessing to building an inverted index and implementing boolean retrieval.

## Overview

The `assignment.ipynb` notebook covers the following key concepts:

1.  **Data Loading**: Importing and exploring a dataset of news articles.
2.  **Text Preprocessing**:
    *   Basic tokenization
    *   Stop word removal
    *   Stemming (using Porter Stemmer)
    *   Lemmatization
    *   Comparison of different preprocessing strategies
3.  **Inverted Index**: Building an inverted index structure to map terms to the documents they appear in.
4.  **Boolean Retrieval**: Implementing boolean logic (AND, OR, NOT) for querying the index.
5.  **Advanced Models** (implied by imports):
    *   Vector Space Models (Word2Vec, Doc2Vec, TF-IDF)
    *   BM25 Ranking
    *   FAISS for efficient similarity search
    *   Clustering (KMeans) and Dimensionality Reduction (PCA)

## Prerequisites

To run this notebook, you need the following Python libraries installed:

*   `pandas`
*   `numpy`
*   `gensim`
*   `rank_bm25`
*   `faiss-cpu` (or `faiss-gpu`)
*   `scikit-learn`
*   `nltk`
*   `matplotlib`
*   `seaborn`

You can install these dependencies using pip:

```bash
pip install pandas numpy gensim rank_bm25 faiss-cpu scikit-learn nltk matplotlib seaborn
```

## Dataset

The notebook expects a dataset file located at `data/Articles.csv`.
The dataset should contain columns such as `Article`, `Date`, `Heading`, and `NewsType`.

## Usage

1.  Ensure the `data` directory exists and contains `Articles.csv`.
2.  Open the notebook:
    ```bash
    jupyter notebook assignment.ipynb
    ```
3.  Run the cells sequentially to execute the code and view the results.

## Features Implemented

*   **Custom Preprocessing Pipeline**: A flexible pipeline that allows toggling stemming and stop word removal.
*   **Inverted Index Construction**: Efficient mapping of terms to document IDs.
*   **Boolean Search**: Functions to perform boolean queries on the indexed documents.
*   **Visualization**: (If applicable based on imports) Visualizing data distributions and model results.

## Acknowledgments

Improvements were made to this assignment to fix errors and refine the markdown descriptions. AI tools like GPT and Claude were used to assist in debugging complex functions and understanding mistakes. Specifically, lines 122-151 were refined with the help of GPT. All AI-suggested changes were manually reviewed and adjusted to ensure they align with the assignment's logic. Comments have been added throughout the code to provide clarification.

## Author

[Mian Usama Arif 
MSCS24016 ]
