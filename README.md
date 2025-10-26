📊 Analyzing Google Play Store App Trends using Python & Power BI
🧠 Project Overview

This project focuses on performing an end-to-end data analysis of the Google Play Store dataset.
You’ll learn how to clean and preprocess real-world data using Python (Pandas, Matplotlib, Seaborn), explore insights through visual analysis, and finally create an interactive dashboard in Power BI that summarizes business insights such as app popularity, ratings, and pricing trends.

🎯 Objectives

Understand the complete data analytics workflow — from raw data to actionable insights.

Develop skills in data handling, preprocessing, visualization, and dashboard design.

Derive business insights and present them using a Power BI dashboard.

🧩 Skills Used

Python: Data cleaning, preprocessing, and exploratory analysis.

Pandas: Data manipulation and feature creation.

Matplotlib & Seaborn: Data visualization.

Power BI: Dashboard creation and KPI visualization.

Google Colab: Cloud-based coding environment.

📘 Learning Outcomes

You will learn to:
✅ Clean and preprocess real-world datasets using Python and Pandas.
📊 Explore and visualize data patterns using Seaborn and Matplotlib.
💡 Derive business insights and create a professional Power BI dashboard.
📈 Think like a data analyst — interpret trends, correlations, and KPIs.

🚀 Project Workflow
Day 1 – Data Loading & Cleaning

Use Google Colab and KaggleHub to import the Google Play Store dataset from Kaggle.

Inspect the dataset using .info(), .describe(), and check for missing or inconsistent values.

Handle missing data, remove duplicates, and clean text-based numeric columns (Price, Installs, Reviews).

Convert data types appropriately and filter invalid entries (e.g., ratings > 5).

Add a derived column isPaid (1 = Paid, 0 = Free).

Save the cleaned dataset as cleaned_playstore.csv.

Day 2 – Exploratory Data Analysis (EDA)

Load your cleaned dataset into Colab.

Explore top app categories and their distributions.

Visualize rating trends using bar plots, histograms, and scatter plots.

Perform correlation analysis between Rating, Installs, Reviews, and Price.

Interpret insights such as:

Which categories are most popular?

Do paid apps have higher ratings?

What factors influence app installs?

Day 3 – Dashboard Creation (Power BI Web)

Go to Power BI
 and sign in with your Microsoft account.

Upload your cleaned_playstore.csv dataset (Create → Upload File → Local File).

Create the following visuals:

📊 Bar Chart – Top 10 app categories by count

🍩 Donut Chart – Free vs Paid app distribution

📈 Line Chart – Average rating by category

💳 Cards (KPIs) – Average Rating, Total Installs

📁 Dataset

Source: Google Play Store Dataset on Kaggle

📉 Sample Insights

Most apps fall under Family, Game, and Tools categories.

Paid apps tend to have slightly higher ratings than free apps.

App installs are strongly correlated with ratings and reviews count.

🧰 Tools & Libraries

Python Libraries: Pandas, Matplotlib, Seaborn

Environment: Google Colab

Visualization Tool: Power BI