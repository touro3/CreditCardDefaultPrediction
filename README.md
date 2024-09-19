# Credit Card Default Prediction - Data Exploration and Cleaning

This project involves exploring and cleaning a dataset related to credit card defaults. The steps followed are based on the book "Projetos Ciência de Dados com Python" from pages 26 to 65. The goal is to prepare the dataset for further analysis and modeling by handling missing data, duplicates, and invalid values.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dependencies](#dependencies)
3. [Data Description](#data-description)
4. [Instructions](#instructions)
5. [Results](#results)

---

## Project Overview

The dataset contains demographic and financial information of credit card holders, along with whether they defaulted on their payments. The task is to perform initial data exploration and cleaning to ensure the dataset is ready for predictive modeling.

## Dependencies

Before running the project, ensure you have the following Python packages installed:

- `pandas`
- `matplotlib`
- `openpyxl` (needed for saving cleaned data as an Excel file)

## Data Description
The dataset is in Excel format (cartao_credito_excel.xls) and contains 30,000 rows with 25 columns. Each row represents a credit card account, and columns include demographic information (e.g., gender, age), financial details (e.g., credit limit, past payments), and whether the customer defaulted on their credit card.

## Results
At the end of this process, we have a clean dataset with:

Corrected data types
No missing values or invalid entries
No duplicate records
Properly categorized data for modeling
The cleaned dataset is saved as cleaned_cartao_credito.xlsx for further analysis and modeling.

## Instructions
Clone this repository or download the project files.
Place the dataset cartao_credito_excel.xls in the dados/ directory.
Set up a Python virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

You can install these dependencies by running:

```bash
pip install -r requirements.txt




