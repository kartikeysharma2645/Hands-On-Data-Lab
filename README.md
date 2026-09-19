# Hands-On Data Lab

A practical Data Science lab covering NumPy, Pandas, data cleaning, visualization, and basic data analysis using Python and Jupyter Notebook.

## Objective

This project demonstrates a practical Data Science workflow, from loading and inspecting raw data to cleaning, feature engineering, visualization, and exploratory analysis.

## Dataset

The project uses the Titanic passenger dataset containing information about passengers, including:

- Passenger class
- Age
- Gender
- Fare
- Family information
- Embarkation port
- Survival status

The original dataset is stored in `data/train.csv`.

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Project Workflow

1. NumPy fundamentals
2. Pandas fundamentals
3. Dataset loading and inspection
4. Missing-value analysis and handling
5. Duplicate and categorical-value inspection
6. Numerical data analysis
7. Feature engineering
8. Data visualization
9. Correlation analysis
10. Key findings and conclusions

## Data Cleaning

The dataset was cleaned by:

- Imputing missing `Age` values using median age by passenger class and gender.
- Filling missing `Embarked` values using the mode.
- Removing the `Cabin` column because approximately 77% of its values were missing.
- Verifying that no missing values remained after cleaning.

## Feature Engineering

Two new features were created:

- `FamilySize` — calculated using `SibSp + Parch + 1`.
- `FamilyType` — categorizes passengers as `Alone`, `Small Family`, or `Large Family`.

Age groups were also created for exploratory analysis.

## Analysis

The project explores survival patterns across:

- Gender
- Passenger class
- Family type
- Age group
- Embarkation port

Correlation analysis was also performed on numerical variables.

## Key Findings

- Overall survival rate: **38.38%**
- Female survival rate: **74.20%**
- Male survival rate: **18.89%**
- 1st class survival rate: **62.96%**
- 2nd class survival rate: **47.28%**
- 3rd class survival rate: **24.24%**
- Small Family survival rate: **57.88%**
- Passengers travelling alone: **30.35%**
- Large Family survival rate: **16.13%**

These findings describe patterns observed in the dataset and do not establish causal relationships.

## Repository Structure

```text
Hands-On-Data-Lab/
├── data/
│   ├── train.csv
│   └── titanic_cleaned.csv
├── notebooks/
│   └── hands_on_data_lab.ipynb
├── README.md
├── requirements.txt
└── .gitignore

## Project Outcome

This project demonstrates a complete hands-on Data Science workflow using a real-world dataset, including data preparation, transformation, visualization, and exploratory analysis.

## Author

**Kartikey Sharma**

## ⭐ Support

If you found this project useful or interesting, consider giving this repository a ⭐ on GitHub!