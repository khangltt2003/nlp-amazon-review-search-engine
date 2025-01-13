# Amazon Review Search Engine

This repository contains the **Amazon Review Search Engine**, a Python-based project that utilizes advanced **Natural Language Processing (NLP)** techniques to retrieve relevant reviews from over 200,000 Amazon product reviews based on user input.

---

## Features

- **Boolean Search**: Implements keyword-based search for quick and direct review retrieval.
- **Topic Modeling**: Utilizes NLP methods to group reviews by underlying topics for better organization and relevance.
- **Word Embeddings**:
  - Integrates **Word2Vec** to understand semantic similarity between user queries and reviews.
  - Enhances retrieval by matching conceptually similar terms.
- **Transformer-Based Models**:
  - Employs **BERT** to capture contextual relevance in review extraction.
  - Significantly improves accuracy for complex and nuanced queries.
- **Rating Filtering**: Filters reviews based on user preferences for specific product ratings.

---

## Achievements

- **Relevance Optimization**:
  - Combined Word Embedding and Rating Filtering methods to achieve up to **80% relevance** in review extraction.
- **NLP Techniques**: Designed and evaluated multiple NLP approaches to enhance the accuracy and efficiency of the search engine.

---

## Technologies Used

- **Python**: Core programming language for backend logic and NLP workflows.
- **NLTK**: For preprocessing tasks like tokenization, stemming, and stopword removal.
- **Gensim**: For implementing **Word2Vec** and topic modeling.
- **BERT**: A transformer-based model for semantic understanding and contextual review matching.
