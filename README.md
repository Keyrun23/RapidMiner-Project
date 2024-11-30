# RapidMiner-Project
 
# Shop Customer Data Analysis


## Introduction

This project analyzes a dataset containing information about shop customers, aiming to gain insights into their spending behavior and develop a predictive model for income based on demographic and professional features. The dataset, sourced from Kaggle, includes 2,000 records and 8 attributes:

- **Customer ID**  
- **Gender**  
- **Age**  
- **Annual Income**  
- **Spending Score** (based on customer behavior)  
- **Profession**  
- **Years of Work Experience**  
- **Family Size**

### Objective
The main goal of this project is to:
- Perform exploratory data analysis (EDA) to understand the dataset.
- Apply machine learning techniques to predict customers' income based on various attributes.



## Methodology

### 1. **Data Preprocessing**
- **Cleaning**: Removed missing values and handled outliers.  
- **Transformation**: Converted nominal data to numerical values using the `Nominal to Numerical` operator.  
- **Feature Selection**: Selected key features such as `Gender`, `Profession`, `Age`, `Work Experience`, and `Family Size`.

### 2. **Exploratory Data Analysis (EDA)**
- Analyzed the distribution of attributes like `Age`, `Annual Income`, and `Spending Score`.
- Explored relationships between variables using visualizations.

### 3. **Model Development**
- **Algorithm**: Linear Regression was chosen for predicting income based on continuous and categorical data.  
- **Implementation**: Developed a model that predicts income based on gender, profession, age, work experience, and family size.



## Results and Findings

### **Key Insights:**
1. **Spending Behavior**:
   - The `Spending Score` revealed distinct customer behavior patterns, which can help businesses segment customers effectively.
2. **Profession and Income**:
   - Professions like Engineering, Entertainment, and Executive roles are associated with higher income levels.
3. **Demographics and Income**:
   - Family size positively correlates with income, while age and work experience show a slight negative correlation.

### **Model Performance:**
- The linear regression model achieved reasonable predictive accuracy.  
- **Key Coefficients**:  
  - Gender (Male): +0.432  
  - Professions (e.g., Healthcare: +5.716, Engineering: +9.389)  
  - Age: -0.032 (per unit increase)  
  - Work Experience: -0.264 (per unit increase)  



## Challenges Faced
1. **Choice of Algorithm**:
   - Initially, logistic regression was considered but later switched to linear regression due to the continuous nature of income data.
2. **Missing Values**:
   - Preprocessed the dataset to handle missing values effectively.
3. **Feature Engineering**:
   - Converting categorical variables (like `Profession`) into numerical values required careful mapping.



## Team Contributions
- **Dataset Preparation**: Vaishnavi  
- **Project Implementation**: Surya, Nikhitha  
- **Presentations**: Kiran  
- **Documentation**: Vinuthna  



## Dataset Source
The dataset was obtained from Kaggle:  
[Shop Customer Data](https://www.kaggle.com/datasets/datascientistanna/customers-dataset?resource=download)



## Conclusion
This analysis provides valuable insights into customer demographics and spending habits, which can help businesses refine their marketing strategies and product offerings. The developed linear regression model serves as a foundational tool for predicting customer income and enabling data-driven decision-making.

 
