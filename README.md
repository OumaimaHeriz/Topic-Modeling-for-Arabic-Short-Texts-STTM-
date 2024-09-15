# Comparative Analysis of Topic Modeling Algorithms for Arabic Tweets

## Overview

This project aims to compare various topic modeling algorithms to determine which one performs best on Arabic tweets. The evaluation involves applying different algorithms to the dataset and measuring their effectiveness using several metrics. The goal is to identify the most suitable algorithm for analyzing Arabic short texts based on their performance.

## Dataset

The dataset consists of Arabic tweets. These tweets have been preprocessed for analysis, including tokenization, stopword removal, and lemmatization.

## Algorithms

The following topic modeling algorithms are evaluated in this project:

- **Latent Dirichlet Allocation (LDA)**: A generative statistical model that assumes documents are mixtures of topics.
- **Latent Semantic Indexing (LSI)**: Uses singular value decomposition to reduce the dimensionality of the document-term matrix.
- **Hierarchical Dirichlet Process (HDP)**: A non-parametric Bayesian approach that infers the number of topics from the data.
- **Non-Negative Matrix Factorization (NMF)**: Factorizes the document-term matrix into lower-dimensional matrices representing topics and words.
- **Author Topic Model (ATM)**: Models the relationship between authors and topics in documents.
- **LDA with Sequential Data (LDA_SEQ)**: Extends LDA to handle sequential data, capturing topic evolution over time.
- **Probabilistic Latent Semantic Analysis (PAM)**: Introduces a probabilistic framework to capture latent semantic structures.
- **Hierarchical Probabilistic Model (HPM)**: Models hierarchical relationships among topics and documents.
- **Dynamic Topic Modeling (DMR)**: Captures changes in topic distributions over time.

## Evaluation Metrics

The performance of each algorithm is evaluated using the following metrics:

- **c-uci**: Coherence score based on UCI metric.
- **umass**: Coherence score based on the UMass metric.
- **cv**: Coherence score based on the CV metric.
- **cuci**: Coherence score based on the C-UC metric.
- **c-npmi**: Coherence score based on the C-NPMI metric.

## License

This project is licensed by HERIZ OUMAIMA. All rights reserved.

## Contact

For questions or comments, please contact oumaima.heriz8@gmail.com (mailto:oumaima.heriz8@gmail.com).
