# 🎬 Netflix Content Analysis & Dashboard

## 📌 Project Overview
This project analyzes Netflix content data to uncover insights about content distribution, growth trends, audience targeting, and regional availability. 

It combines:
- Data cleaning & preprocessing (Python)
- Exploratory Data Analysis (EDA)
- Recommendation System (NLP)
- Interactive Dashboard (Power BI)

---

## 🎯 Objectives

- Analyze Movies vs TV Shows distribution  
- Understand content growth over time  
- Identify top content-producing countries  
- Explore top genres  
- Analyze audience targeting using ratings  
- Build a content-based recommendation system  
- Create an interactive Power BI dashboard  

---

## 📊 Dashboard Preview

![Dashboard](images/dashboard_preview.png)

---

## 📈 Key Insights

### 📺 Content Distribution
- Movies dominate Netflix content (~70%)
- TV Shows are increasing over time

---

### 📈 Growth Trend
- Significant growth after 2015
- Peak content addition around 2019–2020

---

### 🌍 Country Analysis
- Content is concentrated in a few countries:
  - United States
  - India
  - United Kingdom
- Indicates regional dominance and expansion opportunities

---

### 🎭 Genre Analysis
- Top genres include:
  - International Movies
  - Dramas
  - Documentaries
  - Stand-Up Comedy
- Shows strong global and diverse content strategy

---

### 🎯 Audience Targeting
- Majority content is rated:
  - TV-MA
  - TV-14  
- Indicates focus on mature audience

---

## 🤖 Recommendation System

### 📌 Overview
A content-based recommendation system was built to suggest similar movies and TV shows based on genre and description.

---

### ⚙️ Methodology

- Combined features:
  - Genre (`listed_in`)
  - Description  
- Applied:
  - TF-IDF Vectorization  
  - Cosine Similarity  

---

### 💡 Example

Input:


Output:
- Similar animated/action movies based on content similarity

---

### 📈 Business Value

- Improves user experience  
- Enhances content discovery  
- Increases engagement  

---

## ⚙️ Data Processing Steps

- Removed duplicate records  
- Handled missing values  
- Split multi-value columns:
  - country  
  - genre (`listed_in`)  
- Converted date columns and extracted `year_added`  
- Cleaned duration and other features  
- Used `DISTINCTCOUNT` to avoid duplication issues  

---

## 📊 Dashboard Features

- KPI Cards:
  - Total Titles  
  - Movies  
  - TV Shows  
  - Countries Covered  

- Visualizations:
  - Movies vs TV Shows (Donut)
  - Content Growth Over Time (Line Chart)
  - Top Countries (Bar Chart)
  - Top Genres (Bar Chart)
  - Ratings Distribution (Bar Chart)

- Interactive Filters:
  - Type  
  - Country  
  - Year  
  - Genre  
  - Rating  

---

## 🛠 Tools & Technologies

- Python (Pandas, NumPy)
- Power BI
- Scikit-learn
- NLP (TF-IDF, Cosine Similarity)
- Jupyter Notebook

---

## 📁 Project Structure
Netflix-Content-Analysis/
│
├── data/
│ └── netflix_cleaned.csv
│
├── notebook/
│ └── netflix_analysis.ipynb
│
├── dashboard/
│ └── netflix_dashboard.pbix
│
├── images/
│ └── dashboard_preview.png
│
└── README.md


---

## 🚀 Key Learnings

- Data cleaning is critical for accurate insights  
- Multi-value columns must be normalized  
- DISTINCTCOUNT is essential after data expansion  
- Dashboard design improves usability  
- Combining analytics + ML adds strong value  

---

## ⚠️ Limitations

- No user-level data (watch history)  
- Content-based recommendation only  
- Static dataset  

---

## 🔮 Future Scope

- Hybrid recommendation system  
- Real-time data integration  
- Deployment using Power BI Service  
- Advanced NLP models  

---

## 📌 Conclusion

This project demonstrates how data analysis, machine learning, and visualization can be combined to generate meaningful insights and improve decision-making for streaming platforms like Netflix.