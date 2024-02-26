# Supervised-Learning-Project

## Project/Goals
The main objectives of this project are as follows:

Develop machine learning models to predict the risk of diabetes based on patient characteristics.
Conduct exploratory data analysis (EDA) to identify key features influencing diabetes risk.
Assess the performance of different algorithms in predicting diabetes.

## Process

### Step 1: Data Collection
Loaded the "Diabetes" dataset from the National Institute of Diabetes and Digestive and Kidney Diseases into a DataFrame.

### Step 2: Exploratory Data Analysis and Pre-processing

#### A) Analyzed and visualized relationships between variables:
- Explored the dataset, visualized relationships between variables, and gained insights into the data distribution and patterns.
- Using heatcharts, boxplots and histograms.

#### B) Handled missing values and outliers:
- Identified and addressed missing values and outliers in the dataset to ensure data quality and reliability.
- Dropped null values but also explored ways in handling unrealistic values such as "0" for bloodpressure and BMI.

#### C) Performed feature engineering as needed:
- Engineered new features in the "bloodpressure" and "BMI" predictors to improve model performance and capture relevant information from the data.

### Step 3: Model Building

#### Built machine learning models to predict diabetes:
- Utilized supervised learning techniques to train machine learning models for diabetes prediction.

#### Utilized evaluation metrics:
- Evaluated model performance using various evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

#### Selected at least two models, including one ensemble model, and compared their performance:
- Explored different machine learning algorithms and selected two models; the logistic regression and the random forest classifier, to predict diabetes. 
- Compared the performance of the selected models to determine the most suitable approach for the task.

## Results
From the machine learning models developed and the exploratory data analysis conducted, the following findings were obtained:

Features like glucose, BMI, and age appeared to have an importance in predicting diabetes risk, as indicated by their strong correlation with the target variable during our EDA process and their impact on the model's performance.
Both Logistic Regression and Random Forest Classifier had accuracies around 77% on the test set which indicated that both of them showed promising performances in predicting diabetes in a patient.
There are some positives in using one model over the other. The Logistic Regression resulted in a slightly higher accuracy, precision, and ROC-AUC score compared to the Random Forest Classifier (RFC). However, the RFC produced a marginally better recall and F1 score.
Considering in a clinical context, where the cost of missing positive cases may differ from the cost of false alarms, the choice between these models could be tailored to the specific requirements and priorities of healthcare practitioners and institutions. But since we are predicting if someone has diabetes, accuracy and precision might have a more impact determining which model to use. This is because in something important as detecting diabetes in order for proper treatment, a higher accuracy and precicion might be needed.

## Future Goals
If given more time to work on this project, the following future goals could be pursued:

Explore alternative algorithms and techniques for predicting diabetes risk.
Implement other strategies on handling missing values, imbalanced data and scaling.
