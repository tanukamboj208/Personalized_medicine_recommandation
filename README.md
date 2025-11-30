 # Personalized Medicine Recommendation System
# Description
A Medicine Recommendation System is an intelligent machine learning solution designed to assist healthcare professionals in selecting appropriate medicines for patients.The dataset contains medicines, their descriptions, and their associated medical reasons.

## Project Overview

- The goal of this project is to analyze medicine-related text data and build a system that can:

- Identify the relationship between medicine descriptions and their treatment purpose

- Classify medicines based on disease category

- Recommend appropriate medicines when a user provides a medical condition
## Machine Learning Approach

The project uses a TF-IDF based multi-class text classification model using Logistic Regression.
TF-IDF converts textual descriptions into numerical vectors, and Logistic Regression is used to predict the disease category associated with a medicine.
# Key Components

Data Cleaning & Preprocessing:
Stopword removal, text normalization, and TF-IDF vectorization.

Model Training:
Logistic Regression trained on 80% of the dataset with stratified sampling.

Evaluation:
Model achieved 98.55% accuracy, demonstrating strong learning capability from textual patterns.

Recommendation System:
A TF-IDF + Cosine Similarity based engine that recommends relevant medicines when a user inputs a disease name.

# Overview
![Output][]
