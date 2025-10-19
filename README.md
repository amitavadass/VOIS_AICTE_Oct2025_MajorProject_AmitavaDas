🎬 Netflix Content Trends Analysis

Repository: VOIS_AICTE_Oct2025_MajorProject_AmitavaDas

📌 Overview

This project analyzes a dataset of Netflix Movies and TV Shows to understand how the platform’s content has evolved over time. The study explores:

Growth trends in Movies vs TV Shows

Genre popularity

Country-wise contributions

Changes in ratings and release patterns

The goal is to uncover strategic insights into Netflix’s content priorities and global expansion.

🧰 Tools & Technologies

Python 3.x

Pandas – data cleaning and manipulation

Matplotlib & Seaborn – static visualizations

Plotly – interactive charts

Google Colab – development environment

🧹 Data Preprocessing

Major steps performed:

Filled missing values in Release_Date and Release_Year using median imputation

Converted Release_Date to proper datetime format

Derived Release_Year column

Cleaned and standardized text fields (trimmed whitespace, replaced blanks with “Unknown”)

Preserved all records and columns to maintain dataset completeness

📊 Visualizations

The following charts were generated:

Movies vs TV Shows (2008–2021)

Top 10 Most Common Genres

Top 10 Contributing Countries

Content Rating Distribution

Titles Added per Year

🔍 Key Findings

Netflix has consistently hosted more Movies than TV Shows

Content growth peaked around 2019

Popular genres include International Movies and Dramas

Leading content contributors: USA, followed by India and UK

TV-MA is the most frequent rating, indicating a tilt toward mature content

✅ Objectives Completed

✔ Dataset loaded and cleaned
✔ Missing values imputed
✔ Movies vs TV Shows trend identified
✔ Year-wise growth analyzed
✔ Genre and country distributions explored
✔ Rating trends visualized

📈 Strategic Insights

Netflix is expanding internationally through diverse regional content

TV Shows are on the rise, reflecting long-form engagement strategy

Emerging markets like India and Korea offer further content opportunities

Genre variety signals a focus on global audience appeal

💾 Dataset Details

Total Records: 7,789
Columns (11):
Show_Id, Category, Title, Director, Cast, Country, Release_Date, Rating, Duration, Type, Description

▶️ How to Run the Project

Open the notebook in Google Colab

Upload the dataset (Netflix Dataset.csv) or connect Google Drive

Run all cells to perform:

   Preprocessing

   EDA

   Visualization

   Insight generation
