# Letter Recognition Modelling 

## Project Overview
This project focuses on letter recognition using classical data science techniques. The aim is to develop accurate classification models capable of identifying alphabetic characters based on extracted numerical features.

The project applies k nearest neighbours and decision tree classifiers to the letter recognition dataset. These models are evaluated and compared to assess their effectiveness in solving a foundational pattern recognition problem that has wide applicability across real world domains such as optical character recognition and document analysis.

The work is presented through a Jupyter Notebook that documents the full modelling pipeline and supports a critical discussion of the modelling decisions and results obtained.

## Motivation
Letter recognition is a fundamental task in machine learning and pattern recognition. It provides a strong test bed for understanding how different algorithms perform on structured, high dimensional data.

By comparing distance based and tree based models, this project highlights the strengths and limitations of each approach and demonstrates how algorithm selection impacts classification performance.

## Dataset Description
The dataset consists of numerical feature representations of handwritten or stylised letters, with each instance corresponding to a single alphabetic character.

Each record includes:
- A set of continuous input features describing letter geometry
- A categorical target variable representing the letter class

The dataset is well suited for supervised learning and is commonly used to benchmark classification algorithms.

## Methodology

### Data Preprocessing
The dataset is explored to understand feature distributions and class balance. Features are prepared for modelling, with scaling applied where required to ensure fair distance based comparisons. The data is split into training and testing sets to enable robust performance evaluation.

### Model Architecture
Two machine learning models are implemented:
- A k nearest neighbours classifier, which predicts labels based on feature similarity
- A decision tree classifier, which learns hierarchical decision rules from the data

Each model is configured with appropriate hyperparameters to balance bias and variance.

### Training Strategy
Models are trained on the training dataset and evaluated on unseen test data. Hyperparameter tuning is performed to identify suitable values for parameters such as the number of neighbours in KNN and tree depth in the decision tree model.

Model performance is compared using consistent evaluation criteria.

## Evaluation
Performance is assessed primarily using classification accuracy. Additional evaluation includes confusion matrices and classification reports to analyse class level behaviour and misclassification patterns.

The results are discussed critically, with attention given to model interpretability, generalisation performance, and computational considerations.

## Skills Demonstrated

- Supervised machine learning
- Classification using k nearest neighbours and decision trees
- Feature scaling and data preprocessing
- Model comparison and evaluation
- Critical analysis of modelling decisions
- Reproducible experimentation using Jupyter Notebooks
