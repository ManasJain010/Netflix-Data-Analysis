Netflix Data Analysis
📌 Project Overview

This project performs an exploratory data analysis (EDA) on a Netflix dataset. The goal is to clean, analyze, and visualize trends in movies and TV shows such as genre distribution, release patterns, and other key insights.

🛠️ Technologies Used

Python

NumPy

Pandas

Matplotlib

Seaborn

📂 Dataset

The analysis is based on mymoviedb.csv, which contains information about Netflix titles such as:

Title

Genre

Release Date

Other attributes

🔑 Key Steps in Analysis

Data Loading & Cleaning

Read dataset into Pandas DataFrame

Handle duplicates

Convert release dates into proper datetime format

Drop irrelevant columns

Exploratory Data Analysis (EDA)

Dataset info and descriptive statistics

Distribution of genres

Release trends over the years

Correlation checks

Data Visualization

Bar plots, line plots, and histograms for better insights

Genre-wise analysis using Seaborn

📊 Results & Insights

Identified most popular genres on Netflix

Observed trends in releases over different years

Cleaned dataset for reliable analysis

🚀 How to Run

Clone this repository:

git clone <your-repo-link>
cd Netflix-Data-Analysis


Install dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook:

jupyter notebook "Netflix Data Analysis.ipynb"

📌 Future Improvements

Add interactive dashboards (e.g., using Plotly or Streamlit)

Apply machine learning models for prediction (e.g., genre classification or popularity trends)
