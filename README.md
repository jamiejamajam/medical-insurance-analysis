# Medical Insurance Cost Analysis

## Project Overview

This project explores a real-world medical insurance dataset to identify the key factors that influence insurance charges. Using Python and exploratory data analysis (EDA) techniques, the analysis investigates how variables such as age, smoking status, BMI, and number of children relate to medical insurance costs.

The objective was to uncover meaningful patterns within the data, generate visual insights, and develop a strong foundation for future predictive modelling projects.

---

## Dataset Information

The dataset contains **1,338 observations** and **7 variables**:

| Variable | Description |
|-----------|-------------|
| age | Age of the individual |
| sex | Gender of the individual |
| bmi | Body Mass Index |
| children | Number of dependent children covered |
| smoker | Smoking status (yes/no) |
| region | Residential region in the United States |
| charges | Individual medical insurance costs |

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Analysis Performed

### 1. Data Loading and Initial Exploration

The dataset was imported using Pandas and examined to understand its structure, data types, and overall quality.

The analysis confirmed that:

- The dataset contains **1,338 records**
- There are **no missing values**
- Both numerical and categorical variables are present

Key descriptive statistics showed:

- Average age: approximately **39 years**
- Average BMI: approximately **31**
- Average number of children: approximately **1**
- Average insurance charges: approximately **$13,270**

---

### 2. Age vs Insurance Charges

A scatter plot was used to investigate the relationship between age and insurance charges.

#### Findings:

- Insurance costs generally increase with age.
- A positive relationship exists between these variables.
- The data formed distinct bands rather than a single trend line, suggesting additional variables influence insurance charges.

---

### 3. Impact of Smoking on Insurance Charges

Average insurance charges were compared between smokers and non-smokers.

#### Average Charges:

| Smoking Status | Average Charges |
|----------------|----------------|
| Non-Smoker | $8,434 |
| Smoker | $32,050 |

#### Findings:

- Smokers incur substantially higher medical costs.
- Smoking status appears to be one of the strongest predictors of insurance expenses.
- Smoking likely explains much of the variation observed in other visualisations.

---

### 4. BMI vs Insurance Charges

A scatter plot examined the relationship between BMI and insurance charges.

#### Findings:

- Higher BMI values sometimes correspond with increased charges.
- The relationship is weaker and more dispersed than the age relationship.
- BMI alone is not a strong predictor of insurance costs but may contribute when combined with other factors.

---

### 5. Correlation Analysis

Pearson correlation coefficients were calculated between numerical variables.

| Variable | Correlation with Charges |
|-----------|--------------------------|
| Age | 0.299 |
| BMI | 0.198 |
| Children | 0.068 |

#### Findings:

- Age demonstrated the strongest numerical relationship with insurance charges.
- BMI showed a weaker positive association.
- Number of children had minimal predictive influence.
- Smoking status was excluded from the correlation matrix because it is a categorical variable; however, earlier analyses identified it as a major driver of costs.

---

## Key Insights

- Smoking status has the largest impact on medical insurance charges.
- Insurance costs tend to rise with age.
- BMI contributes to higher costs but is not a strong standalone predictor.
- The number of children has little effect on insurance expenses.
- Multiple factors interact to influence medical insurance costs.

---

## Future Improvements

Potential next steps for this project include:

- Converting categorical variables into numerical representations.
- Building predictive machine learning models.
- Evaluating model performance using regression metrics.
- Performing feature engineering to improve predictions.
- Developing interactive dashboards for data exploration.

---

## Repository Structure

```
medical-insurance-analysis/
│
├── insurance_analysis.ipynb
├── insurance.csv
└── README.md
```

---

## Author

**James Parker**

Aspiring Data Analyst with experience in Python, SQL, and exploratory data analysis.

GitHub: https://github.com/jamiejamajam
