# Arxiv34k6l - Multi-label Text Classification Project

## Table of Contents
- [Project Status](#project-status)
- [Overview](#overview)
  - [Objective](#objective)
  - [Dataset](#dataset)
  - [Methodology](#methodology)
- [Contributors](#contributors)
- [License](#license)
- [Acknowledgments](#acknowledgments)

<a id="project-status"></a>
## Project Status
This Project Is Under Development

<a id="overview"></a>
## Overview
Arxiv34k6l is a project aimed at building a multi-label text classification model using natural language processing (NLP) techniques. The project utilizes data sourced from the ArXiv database, which contains a vast collection of academic papers spanning various disciplines.

<a id="objective"></a>
### Objective
The project's main objective is to develop a model capable of accurately classifying academic papers into multiple categories simultaneously based on their abstracts reducing the workload of human reviewers who are often involved, and automating the process.

<a id="dataset"></a>
### Dataset
The dataset used in this project consists of academic papers sourced from the ArXiv. It comprises a diverse range of papers covering topics such as computer science, AI, mathematics, and more. The dataset is preprocessed and annotated for multi-label classification, with each paper associated with one or more subject categories. The data collection process is also done and shown [here](https://github.com/kelixirr/Arxiv34k6l/blob/main/src/data/arxiv34k6l-datasets-collection-process.ipynb). The dataset Arxiv34k6L contains abstracts and their categories (6 labels types with 34068 rows). It has been limited to these many labels for simplicity purposes, and to avoid highly imbalanced classes which are present in ArXiv's data. However, readers can download and preprocess the data according to their own needs as shown in the collection step. 

<a id="methodology"></a>
### Methodology
The project employs various NLP techniques and machine learning algorithms to build an effective multi-label classification model. The methodology includes the following steps:
1. Data Collection: The data used in this project is collected using Arxiv API. 
2. Data Preprocessing: Cleaning and preprocessing the text data for modeling.
3. Model Selection: Evaluating and selecting appropriate machine learning models for multi-label classification, considering factors such as performance metrics and computational efficiency.
4. Model Training: Training the selected model(s) on the preprocessed data to learn patterns and associations between input features and target labels.
5. Evaluation: Assessing the performance of the trained model(s) using metrics such as accuracy, precision, recall, and F1-score.
   
<a id="contributors"></a>
### Contributors
- [Amritesh Kumar](https://github.com/kelixirr)) - Project Lead & Developer

<a id="license"></a>
### License
This project is licensed under the [MIT License](https://github.com/kelixirr/Arxiv34k6l/blob/main/LICENSE).

<a id="acknowledgments"></a>
### Acknowledgments
- Thank you to arXiv for the use of its open-access interoperability.
- Special thanks to [Sayak Paul](https://twitter.com/RisingSayak), and [Soumik Rakshit](https://github.com/soumik12345) for the inspiration behind the project as this project is inspired by their [Large-scale multi-label text classification](https://keras.io/examples/nlp/multi_label_classification/) on Keras.
