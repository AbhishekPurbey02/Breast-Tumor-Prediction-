# Breast-Tumor-Prediction

## Overview

Breast cancer is a pervasive global health challenge, particularly impacting women, with escalating incidence rates. Accurate and timely diagnosis is paramount for effective treatment. This project aims to address the challenges associated with breast cancer diagnosis by employing machine learning algorithms for predictive modeling.

## Problem Definition

The key challenges include developing a robust predictive model capable of classifying breast tumors as benign or malignant. This involves utilizing machine learning algorithms such as K-Means, Decision Tree, Logistic Regression (LR), and Random Forest Classifier.

The complexity of the dataset, which comprises 32 cell attributes, adds another layer of challenge in effectively interpreting and correlating these attributes for accurate predictions. Efficiently partitioning the publicly available breast cancer dataset from Kaggle for training and testing phases is crucial. The dataset will be split, with 75% for training and 25% for testing, ensuring a comprehensive evaluation of the machine learning algorithms.

## Project Objectives

The primary objective is to create a predictive model that enhances the efficiency and accuracy of breast cancer diagnosis. The model will utilize  Decision Tree, Logistic Regression (LR), and ensemble techniques such as Random Forest Classifier algorithms.

## Methodology

The project's scope includes:

1. **Data Collection:** Using a dataset with 32 cell attributes from the UCI Machine Learning Repository.

2. **Data Preprocessing:** Cleaning and preparing the data for analysis.

3. **Model Training:** Employing machine learning algorithms, specifically:
   - Decision Tree
   - Logistic Regression (LR)
   - Random Forest Classifier

4. **Model Evaluation:** Assessing the performance using evaluation metrics like accuracy, precision, recall, and F1-score.

5. **Web Application Development:** Creating a user-friendly interface that takes 32 cell attributes as input and outputs predictions regarding tumor malignancy or benignity.

6. **Deployment:** Integrating the machine learning model into a web application for real-world usage.

## Files

- `TumorPrediction.ipynb`: Jupyter Notebook containing data exploration, preprocessing, and model training code.
- `app.py`: The main application file for running the web server.
- `data.csv`: The dataset used for training and testing the models.
- `firstpic-static.jpg`: An image file used in the web application.
- `form.html`: HTML form for user input in the web application.
- `index.html`: Homepage of the web application.
- `model.pkl`: Serialized machine learning model file.
- `no.html`: HTML file displayed for benign predictions.
- `yes.html`: HTML file displayed for malignant predictions.

## Results

The machine learning model, trained on a dataset of medical imaging data containing relevant tumor features, demonstrated promising performance in predicting breast tumor malignancy. Evaluation metrics indicated that the model could effectively classify tumors with high accuracy.

## Conclusion

The breast tumor prediction project aimed to develop a machine learning-based system for accurately predicting breast tumor malignancy. Through the integration of various components, including data collection, preprocessing, model training, user interface development, and model deployment, the project successfully achieved its goals.

The user interface, designed to be intuitive and user-friendly, provided a seamless experience for users to input tumor data and receive prediction results. Usability testing confirmed that the interface met the needs of users and facilitated efficient interaction with the system.

## Future Directions

Looking ahead, future directions for the project include:

- Incorporating additional data sources
- Improving model interpretability
- Expanding the scope of prediction to include other types of tumors

By building upon the successes and lessons learned from this project, further advancements in breast tumor prediction can be made to benefit patients and healthcare providers alike.
