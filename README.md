**Northbridge University Admissions Analysis**

**Project Overview**

This project applies Python-based data analytics and machine learning to analyse 8,000 undergraduate applications received through two recruitment partners. It examines historical admissions outcomes, recruiter performance, applicant demographics and predictive model performance to evaluate the potential of machine learning as an admissions decision-support tool.

**Objectives**

**The main objectives of this project are to:**

* Integrate and clean two recruiter datasets

* Conduct exploratory data analysis (EDA) and visualisation.
  
* Analyse admissions outcomes by recruiter, gender and ethnicity.
 
* Develop Logistic Regression and Random Forest classification models.
  
* Evaluate predictive performance using appropriate metrics
  
* Assess potential demographic fairness issues.

**Technologies Used**

**The project uses the following technologies and libraries:**

* Programming Language: Python

* Data Analysis: Pandas and NumPy

* Data Visualisation: Matplotlib and Seaborn

* Machine Learning: Scikit-learn

* Model Persistence: Joblib

* Development Environment: Google Colab / Jupyter Notebook

**Dataset Description**

The project uses two datasets: recruiter_A.csv, containing 4,000 applications, and recruiter_B.xlsx, containing another 4,000 applications. The combined dataset contains 8,000 application records.

The target variable is admission_outcome, where 1 represents an offer and 0 represents no offer. Four predictors were used for modelling: prior attainment score, admissions test score, personal statement score and intended subject area. Demographic variables were retained for fairness analysis.

**Key Findings**

* Total applications analysed: 8,000.

* Historical offers: 4,850 (60.62%).

* Historical non-offers: 3,150 (39.38%).

* Recruiter A offer rate: 59.88%.

* Recruiter B offer rate: 61.38%.

* Correlation between academic scores: 0.014.

Logistic Regression achieved 61.38% accuracy and a ROC-AUC of 0.573, while Random Forest achieved 59.88% accuracy and a ROC-AUC of 0.557. Logistic Regression performed comparatively better across most evaluation metrics. However, both models demonstrated limited predictive discrimination.


**Project Workflow**

* Data loading and integration.

* Data cleaning and validation.

* Exploratory data analysis and visualisation.

* Feature preprocessing.

* Logistic Regression and Random Forest model development.

* Model performance evaluation.

* Demographic fairness assessment.

* Model saving and results export.

**Repository Contents**

* Northbridge_University_Admissions_Analysis.ipynb – Main notebook containing data preparation, EDA, visualisations, modelling and evaluation.

* README.md – Project documentation.

* requirements.txt – Required Python packages.

* gitignore – Specifies files excluded from Git tracking.

* recruiter_A.csv and recruiter_B.xlsx – Input datasets, where sharing is permitted.

**How to Run the Project**
* Install dependencies
  
pip install pandas numpy matplotlib seaborn scikit-learn joblib jupyter openpyxl

* Open the notebook
  
jupyter notebook

* Run the analysis
  
Open Northbridge_University_Admissions_Analysis.ipynb, provide both datasets and execute the notebook cells sequentially. Alternatively, upload the notebook to Google Colab.

**Limitations and Responsible Use**

Both models demonstrated limited predictive performance, with ROC-AUC scores below 0.58. The fairness assessment also identified substantial false-positive rates across demographic groups. Therefore, the models are not currently suitable for automated admissions decisions.

Further improvements in data quality, model validation, fairness monitoring, transparency and human oversight are necessary before operational implementation.

**Project Information**
* Project: Northbridge University Admissions Analysis

* Domain: Data Analytics and Machine Learning

* Models: Logistic Regression and Random Forest

* Purpose: Educational and analytical research
