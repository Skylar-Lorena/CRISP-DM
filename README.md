# 🎬 CRISP-DM Movie Studio Data Science Project

## Film Investment & ROI Strategy Analysis

------------------------------------------------------------------------

## 📌 Project Overview

This project applies the **CRISP-DM (Cross-Industry Standard Process for
Data Mining)** framework to support strategic decision-making for a
newly established movie studio.

The studio aims to enter the competitive film industry but faces
financial risk due to limited production experience. Using historical
data on production budgets, box office performance, and audience
reception, this analysis identifies the characteristics of financially
successful films.

The final deliverables include: - A comprehensive Jupyter Notebook
analysis - A Tableau dashboard for stakeholder exploration - Strategic
investment recommendations

------------------------------------------------------------------------

# Business Problem

The company plans to launch a new movie studio and must decide:

-   Which **genres** generate the highest ROI?
-   What **budget levels** are most capital-efficient?
-   How important are **international markets**?
-   Do **audience ratings and popularity** predict commercial success?

> **How can historical movie data guide strategic film investment
> decisions while minimizing financial risk?**

------------------------------------------------------------------------

# Key Metric: Return on Investment (ROI)

ROI is used to measure capital efficiency instead of focusing only on
total revenue.

ROI = (Worldwide Gross − Production Budget) / Production Budget

Interpretation: - ROI = 0 → Break-even\
- ROI = 1 → 100% return\
- ROI \> 1 → Highly profitable\
- ROI \< 0 → Financial loss

------------------------------------------------------------------------

# CRISP-DM Framework Application

## 1️⃣ Business Understanding

Defined the financial risk facing a new studio and identified ROI as the
core performance metric.

## 2️⃣ Data Understanding

Explored datasets to evaluate: - Revenue trends - Budget distribution -
Ratings behavior - Genre frequency - Studio dominance

## 3️⃣ Data Preparation

-   Cleaned currency values
-   Converted gross and budget columns to numeric
-   Standardized movie titles
-   Extracted release year
-   Merged datasets using title and year
-   Engineered ROI feature

## 4️⃣ Data Analysis

Performed: - Domestic vs foreign revenue comparison\
- Revenue trends over time\
- Studio performance comparison\
- Ratings distribution and vote behavior\
- Correlation analysis (Pearson & Spearman)\
- Budget vs ROI analysis\
- ROI by genre (minimum sample threshold applied)\
- Ratings vs worldwide gross analysis

## 5️⃣ Evaluation

Assessed: - Whether ratings predict revenue\
- Whether larger budgets guarantee higher ROI\
- Which genres are most capital-efficient\
- The role of international markets

## 6️⃣ Deployment

Delivered: - A consolidated final notebook\
- Clear visualizations tied to business questions\
- A Tableau dashboard for interactive stakeholder exploration\
- Strategic investment recommendations

------------------------------------------------------------------------

# 📊 Data Sources

The final analysis uses cleaned datasets from:

### Box Office Mojo (BOM)

-   Domestic gross revenue\
-   Foreign gross revenue\
-   Studio\
-   Release year

### The Numbers

-   Production budget\
-   Release date

### IMDb

-   Genres\
-   Average rating\
-   Number of votes

Datasets were cleaned and merged using `title_clean` and release year.

------------------------------------------------------------------------

# 📈 Key Findings

-   International markets generate significantly more revenue than
    domestic markets.
-   ROI varies widely by genre.
-   Mid-budget films often outperform large blockbusters in ROI.
-   High IMDb ratings do not strongly predict high revenue.
-   Budget size alone does not guarantee profitability.
-   Release timing influences revenue performance.

------------------------------------------------------------------------

# Strategic Recommendations

The studio should:

-   Prioritize genres with consistently high average ROI.
-   Focus on international market appeal and distribution strategy.
-   Invest in capital-efficient mid-budget films.
-   Treat IMDb ratings as a quality indicator, not a revenue predictor.
-   Optimize release timing around high-revenue windows.

------------------------------------------------------------------------

# 📊 Tableau Dashboard

The Tableau dashboard (located in the `/tableau/` folder) provides
interactive exploration of:

-   ROI by genre\
-   Budget vs revenue relationships\
-   Studio performance\
-   Revenue trends

------------------------------------------------------------------------

# Repository Structure
```bash
CRISP-DM/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── film_investment_roi_analysis.ipynb
│
├── tableau/
│
├── visuals/
│
├── requirements.txt
├── README.md
└── .gitignore
```
------------------------------------------------------------------------

# ⚙️ Setup Instructions

1.  Clone the repository\
    git clone `https://github.com/Skylar-Lorena/CRISP-DM`

2.  Create a virtual environment (recommended)\
   ``` python -m venv venv```

3.  Activate environment\
    Windows: venv`\Scripts`{=tex}`\activate  `{=tex} Mac/Linux: ```source
    venv/bin/activate```

4.  Install dependencies\
    ```pip install -r requirements.txt```

5.  Run Jupyter Notebook\
    jupyter notebook\
    Open: film_investment_roi_analysis.ipynb

------------------------------------------------------------------------

# 👥 Authors

Ainsley Nyambura\
Lorenah Mbogo\
Angela Mutiaga\
Dennis Kamuri\
Stephen Bwanamkubwa
