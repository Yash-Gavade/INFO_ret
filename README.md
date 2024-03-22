## Information retrieval

![image](https://github.com/Yash-Gavade/INFO_ret/assets/74112721/68ed1312-18b9-4082-bac5-4eda5331517f)

## Introduction
Information retrieval systems play a crucial role in managing and accessing vast amounts of textual data efficiently. With the proliferation of online content, there's a growing demand for search engines capable of providing relevant and accurate results quickly. In this project, we aim to develop a sophisticated search engine by leveraging different search models and machine learning algorithms, including binary search, TF-IDF, word embeddings, K-Means clustering, and K-Nearest Neighbors (KNN). By combining these techniques, we strive to enhance the search experience and improve the retrieval of relevant information from large datasets.

## Motivation
The motivation behind this project stems from the need for advanced information retrieval systems that can handle diverse types of textual data effectively. Traditional search engines often rely on basic keyword matching techniques, which may not always yield optimal results. By incorporating more advanced models and algorithms, we can overcome limitations such as ambiguity in queries, variations in language usage, and the need for context-aware retrieval. Additionally, by utilizing machine learning techniques like clustering and classification, we can automate the process of organizing and labeling data, further enhancing the search experience.

### Dataset
We utilize two datasets in this project:

        Small Dataset: This dataset contains approximately 7,000 news articles without category labels.<br>
        Large Dataset: Consisting of 50,000 news articles categorized into five classes: sport, economy, politics, culture, and health.<br>
        The larger dataset serves as a resource for training machine learning models and for clustering articles into categories, which facilitates labeling the smaller dataset. Both datasets are essential for building and evaluating the search engine's performance.<br>

### Approach
  Inverted Index Model: We first construct an inverted index model to efficiently map terms to the documents they appear in, enabling fast retrieval during search operations.<br>
  Zipf and Heaps Law Analysis: Analysis of Zipf's law and Heap's law helps us understand the distribution of terms and estimate the vocabulary size, guiding optimization efforts.<br>
  K-Means Clustering: We apply K-Means clustering to the larger dataset to group similar articles together based on their content. This clustering aids in categorizing articles and improving search efficiency.<br>
  K-Nearest Neighbors (KNN): Using the clustered data, we employ KNN to label articles in the small dataset based on their similarity to clusters in the larger dataset.<br>
  Search Models: We implement various search models including binary search, TF-IDF, word embeddings, K-Means, and KNN to retrieve relevant articles based on user queries.<br>

### Results
Upon implementing the search engine with different models and algorithms, we evaluate its performance based on metrics such as precision, recall, and retrieval time. The results demonstrate the effectiveness of our approach in providing accurate and efficient search results. By leveraging advanced techniques like clustering and machine learning, we achieve significant improvements in search quality and user experience compared to traditional keyword-based search engines. Overall, our search engine offers a robust solution for information retrieval from large textual datasets.
