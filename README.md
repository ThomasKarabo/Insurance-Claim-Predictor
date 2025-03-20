# Insurance-Claim-Predictor
I analyzed a medical insurance cost dataset to identify key factors influencing insurance charges. To develop a predictive model, I first implemented a Ridge Regression approach. To improve performance, I then applied a Random Forest Regressor. While there’s no improvement, I believe this is due to the relatively small dataset.
Project Overview

This project analyzes a medical insurance cost dataset to explore and predict the factors influencing insurance charges. The dataset was cleaned and preprocessed using SQLite before being imported into a pandas DataFrame for further analysis.

## Objectives

Perform data cleaning and preprocessing to ensure consistency and quality.

Analyze key factors influencing insurance costs.

Implement predictive models to estimate insurance charges.

Compare model performances to improve prediction accuracy.

## Methodology

### Data Cleaning & Preprocessing:

Used SQLite for data transformation and cleaning.

Handled missing values and ensured consistency.

### Exploratory Data Analysis (EDA):

Identified relationships between features and insurance charges.

Visualized data distributions and correlations.

### Model Implementation:

Ridge Regression: Achieved an initial accuracy of 81.5%.

Random Forest Regressor: Improved model performance by 1%, though limited by dataset size.

### Key Findings

Certain features strongly influence insurance charges, such as age, BMI, and smoking status.

The Ridge Regression model provided a strong baseline for predictions.

The Random Forest model slightly improved accuracy, showcasing the impact of ensemble methods.

Dataset size and feature engineering play crucial roles in predictive performance.

Technologies Used

Languages: Python

Libraries: pandas, NumPy, scikit-learn, matplotlib, seaborn

Database: SQLite

### How to Run

Clone the repository:

git clone https://github.com/your-username/medical-insurance-cost.git

Navigate to the project folder:

cd medical-insurance-cost

### Install dependencies:

pip install -r requirements.txt

Run the Jupyter Notebook to explore the analysis and models.

### Future Improvements

Expanding the dataset for better generalization.

Exploring deep learning models for improved accuracy.

Incorporating additional features for enhanced prediction power.
