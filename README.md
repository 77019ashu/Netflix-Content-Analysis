# 🎥 Netflix Content Analysis and Visualization

This project explores and visualizes the Netflix dataset to gain insights into the platform’s content library. It focuses on understanding content distribution, popular genres, top-producing countries, ratings, and release year trends.

---

## 📌 Features & Analysis
- **Data Cleaning**
  - Handled missing values in columns like `director`, `cast`, `country`, `date_added`, and `rating`.
  - Converted `date_added` to datetime format.
  - Extracted and standardized **duration** (minutes vs. seasons).

- **Exploratory Data Analysis (EDA)**
  - Distribution of **Movies vs. TV Shows**.
  - Top 10 most common **genres**.
  - Top 10 **countries** producing Netflix content.
  - Distribution of **age ratings** (e.g., TV-MA, PG-13).
  - Content distribution across **release years**.
  - Top 10 **directors** on Netflix.
  - Monthly addition trends of Netflix content.

- **Visualizations**
  - Count plots, bar charts, histograms, and distribution plots using **Matplotlib** and **Seaborn**.

---

## 🛠️ Tech Stack
- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib & Seaborn** – data visualization

---

## 📊 Insights
- Netflix has a **larger share of Movies compared to TV Shows**.  
- The most common genres include **Dramas, Comedies, and Documentaries**.  
- The USA and India are among the **top contributors of content**.  
- **TV-MA** is the most frequent age rating.  
- The number of Netflix titles increased significantly in the **last decade**.  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/netflix-content-analysis.git
   cd netflix-content-analysis
Install dependencies:
pip install -r requirements.txt
Run the notebook:
jupyter notebook "Netflix Content Analysis and Visualization.ipynb"
📌 Future Improvements
Perform genre-wise trends across years.
Create interactive dashboards with Plotly or Streamlit.
Build a recommendation system based on genres and ratings.
📂 Project Structure
Netflix Content Analysis/

│── Netflix Content Analysis and Visualization.ipynb   # Main notebook
│── netflix_titles.csv                                 # Dataset
│── requirements.txt                                   # Dependencies
│── README.md                                          # Documentation
