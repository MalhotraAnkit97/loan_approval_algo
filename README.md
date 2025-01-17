<img width="770" alt="image" src="https://github.com/user-attachments/assets/986a4031-7d51-4f61-969e-26e1c3a52115" />
# **Loan Approval Decision-Making**

## **Project Overview**
This repository focuses on a data-driven analytical approach to predicting loan approval outcomes. The goal is to enhance financial decision-making processes by building machine learning models that can classify loan applications as approved or rejected based on various applicant and loan characteristics.

---

## **Key Features**
- **Data Analysis**: Comprehensive exploratory data analysis (EDA) to identify trends, outliers, and significant predictors.
- **Feature Engineering**: Encoding categorical variables, handling missing values, and preparing the dataset for modeling.
- **Predictive Modeling**: Comparison of machine learning models including:
  - K-Nearest Neighbors (KNN)
  - Linear Discriminant Analysis (LDA)
  - Neural Networks
  - Multinomial Naive Bayes
  - CatBoost
  - Random Forest
  - Decision Tree
- **Performance Metrics**: Evaluation of models based on accuracy, precision, recall, F1-score, and confusion matrices.

---

## **Dataset Description**
The dataset contains 381 loan applications, reduced to 308 after handling missing values. It includes 13 variables capturing demographic, financial, and loan-specific attributes. The target variable `Loan_Status` is binary:
- `1`: Loan approved
- `0`: Loan rejected

### **Variables**
1. **Gender**: Male/Female
2. **Married**: Applicant’s marital status
3. **Dependents**: Number of dependents
4. **Education**: Graduate/Non-Graduate
5. **Self_Employed**: Employment type
6. **ApplicantIncome**: Income of the primary applicant
7. **CoapplicantIncome**: Income of the co-applicant
8. **LoanAmount**: Requested loan amount
9. **Loan_Amount_Term**: Duration of the loan
10. **Credit_History**: Credit history score
11. **Property_Area**: Urban, Semiurban, or Rural
12. **Loan_Status**: Target variable (1 = Approved, 0 = Rejected)

---

## **Project Workflow**
1. **Data Preparation**:
   - Handled missing values by removing incomplete records.
   - Encoded categorical variables for statistical and machine learning compatibility.
   - Scaled features to normalize the data.

2. **Visualization**:
   - Analyzed variable distributions, relationships, and trends using graphs like histograms, boxplots, and violin plots.
   - Created a correlation matrix to identify relationships between predictors.

3. **Model Building**:
   - Trained multiple machine learning models.
   - Standardized features to ensure consistent scaling.

4. **Evaluation**:
   - Used metrics such as accuracy, precision, recall, and F1-score to evaluate model performance.
   - Confusion matrices to analyze misclassifications.

---

## **Results**
- **Best Model**: Linear Discriminant Analysis (LDA)
  - Accuracy: 87%
  - F1-Score: 91%
- Multinomial Naive Bayes and Random Forest also performed well with accuracies of 85% and 84%, respectively.
- Models like KNN and Decision Trees had lower accuracy and F1-scores.

---

## **Install the Required Libraries**
- **R**: `tidyverse`, `caret`, `ggplot2`

To generate the analysis:
1. Open `analysis_code.Rmd` in RStudio.
2. Knit the file to produce the analysis report.

---

## **Contributing**
Contributions are welcome! Please:
1. Fork the repository.
2. Create a feature branch.
3. Submit a pull request with a detailed explanation of your changes.

---

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for details.
