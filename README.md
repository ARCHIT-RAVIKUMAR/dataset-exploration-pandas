# Netflix Movies & TV Shows Dataset Exploration

## 📌 Project Overview

This project explores the **Netflix Movies & TV Shows** dataset using **Pandas** to understand its structure, identify potential business problems, and frame an appropriate Machine Learning (ML) approach. The analysis includes basic exploratory data analysis (EDA) and key insights that can support data-driven decision-making.

---

## 📂 Dataset Overview

The dataset contains information about movies and TV shows available on Netflix, including details such as:

- Title
- Content Type (Movie/TV Show)
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre
- Description

The purpose of this dataset is to analyze Netflix's content library and uncover patterns that can help improve business decisions.

---

## 💼 Business Problem

Netflix aims to improve its content strategy by understanding the characteristics of its existing catalog. One possible business problem is:

> **Can we predict whether newly acquired content should be categorized as a Movie or a TV Show based on its attributes?**

Accurately predicting the content type can support:
- Content acquisition decisions
- Recommendation systems
- Production planning
- Catalog management

---

## 🤖 Machine Learning Problem Framing

**Problem Type:** Classification

Since the objective is to predict one of two predefined categories (**Movie** or **TV Show**), this is a **Classification** problem.

### Target Variable

- `type`

### Key Features

- `release_year`
- `country`
- `listed_in`
- `rating`
- `duration`
- `director`

---

## 📊 Dataset Exploration

The following exploratory analysis was performed using **Pandas**:

- Dataset shape
- Data types
- Missing values
- Summary statistics
- Duplicate row check
- Distribution of Movies vs TV Shows
- Content ratings
- Top producing countries
- Most common genres
- Release year distribution

---

## 🔍 Key Observations

1. **Movies dominate the Netflix catalog**, making up a larger share of the dataset compared to TV Shows.

2. **Most content was released after 2015**, indicating significant growth in Netflix's content library over recent years.

3. **Several columns, including `director`, `cast`, and `country`, contain missing values**, highlighting the need for data preprocessing before building any machine learning model.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📁 Repository Structure

```
epochs26-day01-dataset-exploration/
│
├── analysis.ipynb
├── README.md
└── netflix_titles.csv
```

---

## 📌 Conclusion

This project demonstrates how exploratory data analysis can help understand a real-world dataset, identify meaningful business problems, and determine a suitable machine learning approach. The insights gained from the Netflix dataset provide a strong foundation for building predictive models and making data-driven business decisions.
