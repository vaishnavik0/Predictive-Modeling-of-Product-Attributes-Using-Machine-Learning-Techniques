<h1 align="center">Predictive Modeling of Product Attributes Using Machine Learning Techniques</h1>
<p align="center">
<img src= "https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue"/>
<img src ="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src = "https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src = "https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
<img src = "https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white"/>
<img src = "https://img.shields.io/badge/UMAP-v0.5+-blue.svg"/>
<img src = "https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252"/>

## Overview
This repository contains all the resources and code for my Machine Learning Project at Dublin City University, focusing on advanced machine learning techniques to improve e-commerce product categorization.

## Project Description
The primary goal of this project was to apply machine learning models to predict various product attributes from an e-commerce dataset, which includes:
- Top and bottom category IDs
- Primary and secondary color IDs

I aimed to maximize the F1 score for each class and attribute, employing models such as Naive Bayes, Logistic Regression, and Gradient Boosting housed within a MultiOutputClassifier framework. A significant part of the project also involved visualizing data embeddings using UMAP and optimizing model performance with K-Means clustering.

## Technologies Used
- **Python**: Main programming language
- **Scikit-learn**: For implementing machine learning models
- **UMAP**: For data dimensionality reduction and visualization
- **Matplotlib & Seaborn**: For plotting and visualizing data

## Results
- The Logistic Regression model performed exceptionally, with the highest F1 score of 0.7133 among the tested models.
- Data visualizations created with UMAP provided insightful clustering that helped in understanding the data’s intrinsic structures.
- The use of the Elbow method in K-Means clustering helped determine the optimal number of clusters to enhance model training efficiency.

## Conclusion
This project provided deep insights into the practical challenges of applying machine learning in an e-commerce setting, improving not just my technical skills but also providing a comprehensive understanding of model application in real-world scenarios.

For a detailed report on the findings and methodology, refer to the full paper included in this repository.
