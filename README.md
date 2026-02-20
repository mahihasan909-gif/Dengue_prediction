# Dengue Prediction

This project aims to predict the risk of Dengue based on parameters derived from blood test features.

## Features Used
- **Age**
- **Sex**
- **Haemoglobin**
- **WBC Count**
- **Differential Count**
- **RBC PANEL**
- **Platelet Count**
- **PDW**

## Final Output
The model predicts the final risk of Dengue.

## Exploratory Data Analysis (EDA)
This section includes visualizations and a comprehensive analysis of the dataset towards understanding trends and insights.

## Data Preprocessing
- Missing value imputation with median for WBC Count, Platelet Count, PDW, and Final Output.
- Outlier handling using IQR capping.
- One-hot encoding of the Sex feature (drop_first).

## Visualization
A correlation heatmap is included to understand relationships between variables.

## Model Training and Evaluation
This section covers various modeling approaches, their training, and evaluation based on the dataset.

## Instructions for Running the Notebook
- To run this code in **Google Colab**, simply upload your dataset to Colab and specify the dataset path accordingly.
- For local execution, ensure you have your dataset in the working directory and adjust the path accordingly.

## Dependencies
Make sure to install the required libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Remove Flask/app.py web usage.