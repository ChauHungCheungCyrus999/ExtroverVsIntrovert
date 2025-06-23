# Extrovert vs. Introvert Behavior Data Analysis

**Author:** Chau Hung Cheung, Cyrus  
**Version:** 23/6/2025

---

## Overview

This project presents a simple data analysis of personality traits, focusing on extrovert and introvert behavior patterns. Using a publicly available dataset, the notebook explores behavioral variables, cleans and preprocesses the data, and applies classification models to predict personality type.  
The project is intended for learning and demonstration purposes.

---

## Table of Contents

- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Installation & Requirements](#installation--requirements)
- [Usage](#usage)
- [Results](#results)
- [Future Work](#future-work)
- [Acknowledgments](#acknowledgments)
- [License](#license)

---

## Project Structure
├── ExtrovtVsIntrovert.ipynb # Main analysis notebook
├── personality_dataset.csv # Dataset (not included, see Dataset section)
├── README.md # This file

---

## Dataset

- **Source:** [Kaggle - Extrovert vs Introvert Behavior Data](https://www.kaggle.com/datasets/rakeshkapilavai/extrovert-vs-introvert-behavior-data/data)
- **Description:**  
  The dataset contains self-reported behavioral data, including:
    - Time spent alone
    - Stage fear
    - Social event attendance
    - Going outside
    - Drained after socializing
    - Friends circle size
    - Post frequency
    - Personality label (Extrovert/Introvert)
- **Preprocessing:**  
  - Missing values are dropped.
  - Categorical variables are label-encoded for modeling.

---
## Results

- The notebook provides data cleaning, exploratory data analysis, and applies classification models (Logistic Regression, Random Forest) to predict personality type.
- Model performance is evaluated using accuracy and classification reports.
- Visualizations illustrate the distribution of behavioral traits among extroverts and introverts.

---

## Future Work

- Try more advanced models or hyperparameter tuning.
- Explore feature engineering or dimensionality reduction.
- Analyze additional personality traits or external datasets.
- Deploy the model as a simple web app for interactive predictions.

---

## Acknowledgments

- Dataset by [Rakesh Kapilavai on Kaggle](https://www.kaggle.com/datasets/rakeshkapilavai/extrovert-vs-introvert-behavior-data/data)
- Project inspired by open data science learning resources.

---

## License

This project is for educational purposes. Please check the dataset’s original license for usage restrictions.

