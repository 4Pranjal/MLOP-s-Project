# Student Performance Indicator

## Overview

This project aims to analyze the factors affecting students' performance, particularly test scores, using machine learning techniques. The life cycle of a machine learning project, from understanding the problem statement to choosing the best model, will be followed.

## Life Cycle of Machine Learning Project

### 1. Understanding the Problem Statement

The project aims to understand how students' performance (test scores) is affected by various factors such as Gender, Ethnicity, Parental level of education, Lunch, and Test preparation course.

### 2. Data Collection

- **Dataset Source:** [Kaggle - Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977)
- **Description:** The dataset consists of 8 columns and 1000 rows.
- **Files:** The data will be stored in the `data.csv` file under the `artifacts` directory.

### 3. Data Checks to Perform

Before proceeding with analysis, some data checks will be performed to ensure data quality and integrity.

### 4. Exploratory Data Analysis (EDA)

EDA will be conducted to gain insights into the dataset and understand the relationships between variables.

### 5. Data Pre-Processing

Data pre-processing steps such as handling missing values, encoding categorical variables, and scaling numerical features will be performed.

### 6. Model Training

Several machine learning models will be trained using the pre-processed data to predict students' test scores.

### 7. Choose Best Model

The best-performing model will be selected based on evaluation metrics and validation performance.

## Folder Structure

```
├── artifacts
│   ├── data.csv
│   ├── model.pkl
│   ├── preprocessor.pkl
│   ├── test.csv
│   └── train.csv
├── catboost_info
│   ├── data
│   ├── EDA STUDENT PERFORMANCE.ipynb
│   └── MODEL TRAINING.ipynb
├── notebook
│   └── learn_error.tsv
│   └── time_left.tsv
├── src
│   ├── components
│   ├── pipeline
│   ├── __init__.py
│   ├── exception.py
│   └── logger.py
│   └── utils.py
├── templates
│   ├── home.html
│   └── index.html
├── README.md
├── app.py
├── requirements.txt
└── setup.py
```

## Getting Started

To get started with the project, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/4pranjal/machine-learning-projects.git
   ```

2. Navigate to the directory:

   ```bash
   cd machine-learning-projects
   ```

3. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

## Contributors

- [Pranjal Jain](https://github.com/4Pranjal)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
