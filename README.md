# 🎬 JCMDATAMOVIES

**Data project for exploring and analyzing movie datasets using Python.**  
This repository contains a complete Exploratory Data Analysis (EDA), data cleaning process, and preparation for ETL workflows in both Python and Power BI.

---

## 📁 Project Structure

JCMDATAMOVIES/
│
├── Data/
│ ├── raw/ # Raw CSV files (original datasets)
│ │ └── imdb_top_1000.csv
│ └── processed/ # Cleaned dataset ready for analysis
│   └── cleaned_imdb_top_1000.csv
│
├── Notebooks/
│ └── EDA.ipynb # Jupyter Notebook with complete exploratory analysis
│
│
│── README.md



---

## 🔍 Dataset Overview

The main dataset used (`imdb_top_1000.csv`) includes:
- Titles, genres, and certifications
- IMDB ratings and meta scores
- Revenue and number of votes
- Director and top 4 stars
- Release year, runtime, and overview

---

## 🧪 EDA Highlights

Performed using Pandas, Seaborn, Matplotlib, Plotly, and Missingno.

- Data type conversion and cleaning
- Handling of missing values (smart filtering or imputation)
- Analysis by:
  - Genre
  - Year / decade
  - Certificate (ratings like PG-13, R, etc.)
  - Popular actors/directors
- Revenue vs. Ratings correlations
- Saga filtering (e.g., Star Wars)
- Ranking of top-rated and highest-grossing movies

---

## 🛠️ Cleaning & Preparation

- Replaced or removed irrelevant characters (e.g., `min`, `,`)
- Converted data types (e.g., `Year → Int64`, `Certificate → category`)
- Renamed key columns (`No_of_Votes → Votes`, `Gross → Revenue`)
- Dropped unnecessary columns like `Poster_Link`

The cleaned dataset is stored in `Data/processed/cleaned_imdb_top_1000.csv`.

---

## 📊 Next Steps: ETL and Power BI

This dataset is now ready to:
- Be used in Power BI dashboards
- Feed into an ETL pipeline
- Be exported to a SQL database for advanced querying

---

## 🚀 Tools & Technologies

- Python 3.10
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly, Missingno
- Power BI (for future integration)
