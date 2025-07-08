# Banking Risk Analysis - Python, SQL, Tableau 

## Project Overview

This repository presents a comprehensive risk analysis within the banking domain, focusing on identifying key risk indicators and understanding customer behavior. The project leverages a real-world banking dataset to perform exploratory data analysis (EDA), identify correlations, detect outliers, and ultimately pinpoint factors contributing to high-risk customer profiles. The insights gained can be instrumental for banks in making informed decisions regarding loan approvals, fraud detection, and personalized customer service.

## Dataset

The primary dataset used for analysis is `Banking - Banking_Cleaned.csv`, which is a cleaned version of the initial raw data (`Banking_file_from_DF.csv`).

## Files in this Repository

* `Risk_analysis_Bank_Domain.ipynb`: This Jupyter Notebook contains the complete Python code for the banking risk analysis. It includes:
    * Data Loading and Initial Exploration
    * Data Cleaning and Preprocessing
    * Exploratory Data Analysis (EDA)
    * Correlation Analysis to identify relationships between variables (e.g., Credit Score and Loan Approval, Late Payments and Account Balance, Foreign Currency Account and Total Relationship Amount).
    * Outlier Detection and Treatment (e.g., in Loan Amount and Foreign Currency Account values).
    * Identification of Key Risk Indicators (e.g., low credit scores, high number of late payments, low total relationship value, high fee structure with low loyalty classification).
    * Data Visualization using Seaborn and Matplotlib (e.g., heatmaps for correlation, distribution plots for financial metrics, count plots for categorical variables).

* `Banking - Banking_Cleaned.csv`: The cleaned and preprocessed dataset used for the analysis in the Jupyter notebook.

* `Banking_file_from_DF.csv`: The original, raw banking dataset (potentially before extensive cleaning).

* **`Home_page.jpg`**: This image likely represents a screenshot or a visual of the main dashboard or landing page of a banking application or system, providing context for where such data might originate or be utilized.

* **`Loan_page.jpg`**: This image probably depicts a section related to loan applications or loan details within a banking interface. It could illustrate the data points relevant to loan products that are analyzed in this project.

* **`Deposit_page.jpg`**: This image is expected to show a page or section related to deposit accounts and transactions, offering a visual representation of the data pertaining to customer deposits.

* **`Summary_page.jpg`**: This image most likely showcases a summary or overview page, potentially displaying aggregated financial information or key metrics, which could be an output or a visual representation of the insights derived from this risk analysis.

## Analysis Highlights

The `Risk_analysis_Bank_Domain.ipynb` notebook details the following key aspects of the analysis:

* **Data Preprocessing:** Handled missing values, incorrect data types, and performed necessary transformations to ensure data quality.
* **Correlation Analysis:** Discovered strong correlations between critical variables such as "Credit Score" and "Loan Approval," "Late Payments" and "Account Balance," and "Foreign Currency Account" and "Total Relationship Amount." These insights are crucial for prioritizing variables in risk prediction models.
* **Outlier Detection:** Identified and addressed significant outliers in "Loan Amount" and "Foreign Currency Account" values using appropriate capping/trimming techniques to prevent distortion in model inputs.
* **Risk Indicator Identification:** Pinpointed key indicators of high-risk customers, including:
    * Low credit scores
    * High number of late payments
    * Low total relationship value
    * High fee structure coupled with low loyalty classification
* **Data Visualization:** Utilized powerful visualization libraries (Seaborn and Matplotlib) to create insightful plots such as heatmaps for correlation exploration, distribution plots for financial metrics, and count plots for categorical variable analysis.
