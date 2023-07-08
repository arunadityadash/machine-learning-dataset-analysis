# Machine Learning Project: Dataset Analysis and Modeling
This repository contains a machine learning project that focuses on analyzing and modeling a given dataset. The project involves various stages, including data loading, preprocessing, feature engineering, model training, and evaluation. This project was the capstone project for Summer Analytics 2023 by IIT Guwahati.

<h2>Project Overview</h2>

- The goal of this project is to develop predictive models for a specific task using machine learning techniques. The datasets used in this project were provided by Summaer Analytics IIT-G. The target variable 'pred' represents the predicted outcome or class label that we aim to predict using machine learning models. 
- The goal of this project is to develop predictive models using machine learning techniques to accurately predict the value of the target variable based on the given features.
- By analyzing and modeling this dataset, we aim to gain insights into the underlying patterns and relationships within the data and build models that can make reliable predictions for the target variable. The performance of the models will be evaluated using metrics such as precision, recall, and F1 score to assess their effectiveness in solving the given task.

<h2>Contents</h2>

- notebook.ipynb: Jupyter Notebook containing the complete code and analysis for the project.

- Train_Data.csv: The training dataset used in the project.

- Test_Data.csv: The test dataset used in the project.

- predictions.csv: Submission file containing the predictions made on the test data using the best performing model.

<h2>Project Workflow</h2>

**1) Data Loading and Preprocessing:** The dataset is loaded and preprocessed to handle missing values, encode categorical variables, and scale numeric features.

**2) Exploratory Data Analysis (EDA):** Exploratory data analysis techniques are applied to gain insights into the dataset's structure and relationships between variables.

**3) Feature Engineering:** New features are created or existing features are transformed to enhance the predictive power of the dataset.

**4) Model Training and Evaluation:** Multiple machine learning algorithms, including Logistic Regression, Random Forest Classifier, and Support Vector Machine (SVM), are trained and evaluated based on precision, recall, and F1 score.

**5) Selection of Best Model:** The model with the highest F1 score is selected as the best performing model for the task.

**6) Prediction on Test Data:** The best model is used to make predictions on the test data, and the results are stored in the predictions.csv file.

**7) Conclusion:** A summary of the project findings, including the performance of the best model and potential areas of improvement.

Please refer to the notebook.ipynb file for a detailed analysis and step-by-step implementation of the project.

<h2>Requirements</h2>

**Python version:** 3.9.6

**Libraries and versions:**

- pandas==1.3.0

- numpy==1.21.0

- scikit-learn==0.24.2

- matplotlib==3.4.2

- seaborn==0.11.1

- jupyterlab==3.1.7

Feel free to explore the code, modify it, or apply it to your own datasets. If you have any questions or suggestions, please don't hesitate to reach out.

Happy coding!

