🍽️ Restaurant Data Analysis & Recommendation Project
📌 Project Overview

A restaurant consolidator aims to revamp its B2C portal using intelligent automation technologies. This project performs comprehensive Exploratory Data Analysis (EDA) on restaurant datasets to understand data behavior, clean inconsistencies, and derive meaningful insights to identify star restaurants and support recommendation generation.

The analysis focuses on customer engagement, geographical distribution, cuisine trends, delivery options, and factors affecting restaurant ratings. Interactive dashboards are created using Tableau to help visualize insights and support business decision-making.

📊 Datasets

This project uses two datasets:

restaurants_data.xlsx – Contains restaurant details with 19 attributes (ratings, votes, cuisines, cost, delivery, booking, etc.)

Country-Code.xlsx – Contains country codes and corresponding country names

Both datasets are located in the data/ folder.

🛠️ Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook

Tableau (for dashboards)

GitHub (version control)

🔍 Project Objectives
1. Data Inspection & Cleaning

Inspect data structure and attributes

Identify and handle missing values

Detect and remove duplicate records

2. Exploratory Data Analysis (EDA)
Geographical & Business Insights

Analyze geographical distribution of restaurants

Identify cities with maximum and minimum restaurant counts

Explore franchises with the highest national presence

Calculate ratio of restaurants allowing table booking vs not

Determine percentage of restaurants offering online delivery

Compare votes for restaurants with and without delivery

Cuisine & Cost Analysis

Identify top 10 cuisines served across cities

Find maximum and minimum number of cuisines per restaurant

Determine most served cuisine per city

Analyze cost distribution across restaurants

Ratings Analysis

Study distribution of ratings

Analyze factors affecting ratings such as:

Number of cuisines

Cost for two

Online delivery option

Table booking availability

Number of votes

📈 Dashboard & Visualization

Interactive Tableau dashboards created to visualize:

Restaurant distribution by city and country

Cuisine popularity

Ratings vs cost and votes

Delivery and booking trends

Dashboards help identify star restaurants based on multiple performance indicators.

📂 Project Structure
Resaturant/
│
├── data/
│   ├── restaurants_data.xlsx
│   └── Country-Code.xlsx
│
├── notebooks/
│   └── EDA.ipynb
│
├── dashboards/
│   └── tableau_dashboard.twbx
│
└── README.md
✅ Key Outcomes

Cleaned and prepared dataset for analysis

Identified cities and cuisines with highest restaurant presence

Determined key factors influencing restaurant ratings

Built dashboards for business insight and decision-making

Provided a foundation for star restaurant identification and recommendations

🚀 Future Enhancements

Build a recommendation system using machine learning

Automate star restaurant classification

Deploy dashboards as a web application

Integrate real-time data updates



