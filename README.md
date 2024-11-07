# Titanic Dataset: Decision Tree Classifier

This project demonstrates how to apply a Decision Tree Classifier to predict passenger survival on the Titanic dataset from Kaggle. The model is trained using various features available in the dataset and used to predict whether a passenger survived or not.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Results](#results)
- [License](#license)
- [Contact](#contact)

## Overview

In this project, we use the Titanic dataset from Kaggle, which contains information about passengers on the Titanic, such as age, sex, ticket fare, and class. Our goal is to predict whether a passenger survived or not based on these features.

We applied the Decision Tree Classifier, a supervised machine learning algorithm, to fit the data and make predictions. We also evaluated the model's performance using accuracy and other evaluation metrics.

## Dataset

The Titanic dataset is a well-known dataset from Kaggle. It contains information about 891 passengers, including:

- **PassengerId**: A unique ID for each passenger
- **Pclass**: The passenger's class (1st, 2nd, or 3rd)
- **Name**: Name of the passenger
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Fare paid for the ticket
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
- **Survived**: Target variable, 0 = No, 1 = Yes (indicates if the passenger survived)
## Images:
![image](https://github.com/user-attachments/assets/503b89de-e0b0-41e5-b310-da9a5a3e2ef1)
![image](https://github.com/user-attachments/assets/7ac7e0db-b203-45c0-ab05-96b8b8fe2393)
![image](https://github.com/user-attachments/assets/c7774257-05dc-4883-8cb6-9744bc532f6b)


## Methodology

1. **Data Preprocessing:**
   - Loaded and explored the Titanic dataset.
   - Cleaned the data by handling missing values, encoding categorical variables (such as Sex and Embarked), and scaling numerical features where necessary.

2. **Modeling:**
   - Split the data into training and testing sets.
   - Applied the Decision Tree Classifier to the training data.
   - Fitted the model and used it to predict the survival of passengers in the test set.

3. **Evaluation:**
   - Evaluated the model's performance using accuracy, precision, recall, and F1-score.
   - Displayed a confusion matrix and feature importance to understand the model better.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/souravdebnath109/Titanic-dataset-model-train-by-ML.git
