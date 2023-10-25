# Predicting Income with Boosting Algorithms

In this project, I embark on a journey into the realm of boosting algorithms, employing the power of data to forecast an individual's income. By utilizing this census dataset in conjunction with boosting algorithms, my objective is to predict whether an individual's income exceeds $50,000.

**Data Source**: The dataset is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/census+income) and contains information about individuals, including their age, education, work class, hours worked per week, gender, and race.

**Key Project Objectives:**

1. **Data Preprocessing**: The initial step involves cleaning the data by handling extra whitespace, defining the target column (income), and selecting relevant features for analysis.

2. **Data Exploration**: I delve into the dataset to understand the distribution of income levels and the data types of selected features.

3. **Preparing the Features**: To prepare the features for model training, I convert categorical variables into binary dummies and convert the target variable (income) into binary labels. A train-test split is also created for model evaluation.

4. **Model Building and Training**: I create and train two ensemble classifiers - AdaBoost and Gradient Boosting - to classify individuals based on their income. The models are fitted and evaluated based on accuracy and F1-score.

5. **Hyperparameter Tuning**: For the AdaBoost classifier, I perform hyperparameter tuning by varying the number of estimators. I conduct a grid search to find the optimal number of estimators that maximizes the mean test score.

6. **Visualizing the Results**: The project concludes with a visual representation of the mean test scores as the number of estimators varies, helping us identify the optimal parameter setting.

**Summary:**  
This project offers a comprehensive understanding of machine learning model analysis and optimization. Starting with data preprocessing, I dive into exploring the dataset, feature preparation, and model building using ensemble methods. I assess model performance and engage in hyperparameter tuning to fine-tune our classifiers for improved results. Ultimately, the project demonstrates the importance of careful analysis and optimization in the world of machine learning, providing valuable insights for making data-driven decisions.