# COVID-19-Outcome-Prediction
# Project Description
This project aims to develop classifiers to predict the outcome (death/recovered) of individuals with coronavirus symptoms based on pre-defined standard symptoms provided by the World Health Organization (WHO). The dataset used is a time series containing daily information on the number of affected cases, deaths, and recoveries from the 2019 novel coronavirus. The data spans from January 22, 2020, and is stored in the "data.csv" file.

# Dataset Information
The dataset comprises 14 major variables that may impact an individual's recovery, including:

Country: The country where the person resides.
Location: Specific location within the country.
Age: Classification of the age group based on WHO Age Group Standard.
Gender: Male or Female.
Visited_Wuhan: Whether the person has visited Wuhan, China.
From_Wuhan: Whether the person is from Wuhan, China.
Symptoms: Six families of symptoms coded in six fields.
Time_before_symptoms_appear: Time before symptoms appear.
Result: Binary outcome, where 0 represents recovered and 1 represents death.
# Project Goals
The primary objectives of this project are as follows:

1. Data Preprocessing: The dataset is already cleaned and preprocessed, ready for model development.

2. Data Partitioning: Divide the data into three partitions - training, validation, and testing sets.

3. Classifier Design: Develop classifiers for the following algorithms:

 - K-Nearest Neighbors
 - Logistic Regression
 - Naïve Bayes (due end of week 11)
 - Decision Trees
 -Support Vector Machines (due end of week 14)
4. Optimal Hyperparameter Tuning: Find the optimal hyperparameters for each classifier.

5. Performance Metrics: Compare the performance of classifiers using metrics such as precision, recall, F1-score, and ROC/AUC curves.

# Getting Started

1. **Clone the repository:**

   ```bash 
   git clone https://github.com/Heba2h/COVID-19-Outcome-Prediction.git 
   ```
2. **Navigate to the project directory:**
    ``` bash
    cd COVID-19-Outcome-Prediction
    ```
3. **Open the Jupyter notebook or Python script to explore and run the classifiers.**
