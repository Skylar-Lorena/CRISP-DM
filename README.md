# CRISP-DM
## Movie Studio Data Science Project

---

## Project Overview

This project applies the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework to support business decision-making for a newly established movie studio. The studio aims to enter the competitive film industry but lacks prior experience in identifying what types of movies are most likely to succeed financially.

Using historical movie performance data from multiple sources, this analysis explores trends in box office revenue, audience reception, and movie characteristics. The insights generated are translated into clear, actionable recommendations to guide future movie production decisions.

---

## Business Problem

Major entertainment companies are increasingly investing in original film content. To remain competitive, the company plans to launch its own movie studio. However, without prior experience in film production, the studio faces significant financial risk.

The central business question addressed in this project is:

**How can historical movie data be used to identify the characteristics of successful films, and how can these insights inform strategic production decisions for a new movie studio?**

---

## Project Objective

The objective of this project is to provide data-driven insights that help a new movie studio decide which types of films to prioritize for production in order to maximize box office success while managing financial risk.

---

## CRISP-DM Framework

### 1. Business Understanding
Define the business problem and key objectives. In this project, the focus is on understanding what drives box office success and how those drivers can be used to guide production strategy.

### 2. Data Understanding
Explore and describe the datasets used in the analysis, including their sources, structure, time coverage, and limitations. This phase evaluates how well the data supports the business question.

### 3. Data Preparation
Clean and prepare the data for analysis. This includes handling missing values, standardizing variables, and merging datasets where appropriate.

### 4. Data Analysis
Analyze the prepared data to identify patterns and relationships between movie characteristics, audience reception, and box office performance.

### 5. Evaluation
Evaluate whether the analysis sufficiently addresses the business problem and supports actionable recommendations.

### 6. Deployment
Present insights using visualizations and a non-technical presentation, and provide clear recommendations that stakeholders can use for decision-making.

---

## Data Sources

The analysis uses the following datasets:

- **Box Office Mojo**: Box office revenue data, including domestic and international gross.
- **TMDB (The Movie Database)**: Movie metadata such as popularity, audience ratings, and vote counts.
- **The Numbers**: Production budgets and revenue figures.
- **Movie Info**: Additional movie metadata.
- **Movie Reviews**: Audience and critic review data.

---

## Folder Structure

The repository is organized according to the CRISP-DM framework:

```bash
CRISP-DM/
│
├── data/
│   ├── raw/
│   │   ├── im.db
│   │   ├── bom.movie_gross.csv
│   │   ├── tn.movie_budgets.csv
│   │   ├── tmdb.movies.csv
│   │   ├── movie_info.csv
│   │   └── movie_reviews.csv
│   │
│   └── processed/
│
├── notebooks/
│   └── 01_data_understanding_person1.ipynb
│
├── tableau/
│
├── README.md
└── .gitignore
```

## Authors

Ainsley Nyambura

Lorenah Mbogo

Angela Mutiaga

Dennis Kamuri

Stephen Bwanamkubwa