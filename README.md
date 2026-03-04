\# Distributed Machine Learning for Income Classification



\## Project Overview

This project investigates the application of distributed machine learning techniques to classify income levels using a large-scale demographic dataset. The objective is to evaluate the performance and scalability of different machine learning algorithms using PySpark in a distributed computing environment.



The project demonstrates the complete big data analytics pipeline including data ingestion, preprocessing, model training, evaluation, scalability analysis, and visualization.



\## Technologies Used

\- PySpark (MLlib)

\- Databricks

\- Python

\- Tableau Public



\## Machine Learning Models Implemented

The following classification algorithms were implemented and evaluated:



\- Logistic Regression

\- Decision Tree

\- Random Forest

\- Gradient Boosted Trees



\## Evaluation Metrics

Models were evaluated using the following metrics:



\- AUC (Area Under ROC Curve)

\- Accuracy

\- Precision

\- Recall

\- F1 Score



Hyperparameter tuning was performed using PySpark CrossValidator.



\## Scalability Analysis

To analyse the scalability of the distributed machine learning pipeline, models were trained using increasing fractions of the dataset. Training runtime and model performance were recorded to evaluate how computational cost grows with dataset size.



\## Repository Structure



notebooks/

&nbsp;   Databricks notebook containing the PySpark data processing pipeline and machine learning models.



tableau/

&nbsp;   Tableau workbook containing interactive dashboards for data exploration, model performance comparison, feature importance analysis, and scalability evaluation.



data/

&nbsp;   Sample datasets used for visualization and dashboard creation.



README.md

&nbsp;   Project documentation.

