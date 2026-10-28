**Northbridge University Admissions Analysis**

**Project Overview**

This project uses Python-based data analytics and machine learning to analyse 8,000 university applications. It explores historical admissions outcomes, recruiter performance, applicant demographics, and predictive model performance. The analysis aims to identify patterns in admissions decisions and evaluate the effectiveness and fairness of machine learning models.

**Objectives**

**The main objectives of this project are to:**

* Perform data cleaning and data quality checks.

* Conduct exploratory data analysis (EDA) and data visualisation.

* Compare admission outcomes by recruiter, gender, and ethnicity.

* Train and evaluate Logistic Regression and Random Forest classification models.

* Assess model performance using appropriate evaluation metrics.

* Audit model predictions for potential fairness issues.

**Technologies Used**

**The project uses the following technologies and libraries:**

* Programming Language: Python

* Data Analysis: Pandas and NumPy

* Data Visualisation: Matplotlib and Seaborn

* Machine Learning: Scikit-learn

* Model Persistence: Joblib

* Development Environment: Jupyter Notebook

**Key Findings**

The analysis examined 8,000 university applications to understand historical admissions outcomes and evaluate the performance of two machine learning models.

**The main findings are:**

* Total applications analysed: A total of 8,000 applications were included in the analysis.

* Historical offers: Out of these applications, 4,850 resulted in offers.

* Overall offer rate: The historical offer rate was 60.62%, meaning that approximately three-fifths of the applications resulted in offers.

* Logistic Regression performance: The model achieved a ROC-AUC score of 0.573.

* Random Forest performance: The model also achieved a ROC-AUC score of 0.573.

Both models demonstrated limited ability to distinguish between applications that resulted in offers and those that did not. Their identical ROC-AUC scores indicate that neither model performed better than the other according to this evaluation metric.

These findings suggest that further investigation into feature selection, data quality, model configuration, and predictive performance is necessary before either model can be considered for practical admissions decision support.

**Project Workflow**

**The project follows a structured analytical workflow:**

* Data Quality Assessment: Examine missing values, duplicate records, data types, and data consistency.

* Exploratory Data Analysis: Investigate application patterns, historical offer rates, recruiter outcomes, and applicant demographic distributions.

* Feature Preparation: Prepare relevant variables for predictive modelling.

* Model Development: Train Logistic Regression and Random Forest classification models.

* Model Evaluation: Assess predictive performance using classification metrics and visualisations.

* Fairness Auditing: Examine potential differences in admissions outcomes and model predictions across relevant demographic groups.

* Results Export: Export key analytical results and save model artefacts where supported by the notebook.

**Repository Contents**

**The repository contains the following files:**

* Northbridge_University_Admissions_Analysis.ipynb — The Jupyter Notebook containing data preparation, exploratory analysis, visualisations, predictive modelling, and model evaluation.

* README.md — Project documentation, including the overview, objectives, findings, and instructions.

* .gitignore — Specifies files and directories that should be excluded from Git tracking.

* requirements.txt — Lists the Python packages required to run the project.

**How to Run the Project**

**1. Install Dependencies**

Install the required Python packages using pip:

pip install pandas numpy matplotlib seaborn scikit-learn joblib jupyter openpyxl

**2. Open the Notebook**

Launch Jupyter Notebook from your terminal:

jupyter notebook

Open Northbridge_University_Admissions_Analysis.ipynb and execute the notebook cells sequentially.

Alternatively, upload the notebook to Google Colab and run it in the cloud-based environment.

**3. Provide the Input Datasets**

Ensure that the required Recruiter A CSV dataset and Recruiter B Excel dataset are available. If the notebook prompts for file uploads, provide the corresponding datasets and follow the data-loading instructions.

**Limitations and Responsible Use**

The models predict historical admissions decisions rather than future academic success. Both models achieved a ROC-AUC score of 0.573, indicating limited predictive discrimination between offered and non-offered applications.

The results should therefore be interpreted cautiously. Further investigation is required into data quality, class distributions, feature selection, model performance, and potential demographic bias.

Admissions predictions should not be treated as definitive recommendations or used as the sole basis for decisions affecting applicants. Human oversight, data privacy, transparency, and appropriate fairness assessments are essential before considering operational use.

**Author**

* Project: Northbridge University Admissions Analysis

* Domain: Data Analytics and Machine Learning

This project is intended for educational and analytical purposes only.
