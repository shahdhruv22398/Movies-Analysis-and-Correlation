# 🎬 Movies Analysis & Correlation | Python

This project explores relationships between various **movie features** such as ratings, votes, budget, gross revenue, and runtime to understand what factors drive box-office performance. Using Python (Pandas, NumPy, Seaborn, Matplotlib), it performs data cleaning, correlation analysis, and visualization to uncover meaningful insights.

---

## 📊 Dataset Overview
**File:** `movies.csv`  
**Rows:** 7,668  **Columns:** 15  

**Key Columns:**  
- 🎞️ `name`, `genre`, `rating`, `year`, `country`, `company`  
- 💰 `budget`, `gross`  
- ⭐ `score`, `votes`, `runtime`  

**Missing Data:**  
- `budget` → 28.3% missing  
- `gross` → 2.5% missing  
- Minor nulls in `rating`, `runtime`, and `company`

---

## 🧠 Analysis Steps
1. **Data Cleaning** – Handled missing values and standardized data types.  
2. **Exploratory Data Analysis (EDA)** – Generated descriptive statistics and visualized numeric distributions.  
3. **Correlation Analysis** – Examined how numerical features relate to one another using Pearson correlation.  
4. **Visualization** – Created heatmaps and regression plots to visualize relationships.

---

## 📈 Key Insights
- **Budget ↔ Gross Revenue:** Strong positive correlation (**r = 0.74**) — higher budgets often yield higher box-office returns.  
- **Votes ↔ Gross:** Strong correlation (**r = 0.63**) — audience engagement links closely with financial success.  
- **Score ↔ Votes:** Moderate correlation (**r = 0.41**) — higher-rated movies generally attract more viewers.  
- **Score ↔ Gross:** Weak correlation (**r = 0.19**) — critically acclaimed movies don’t always earn more revenue.  
- **Runtime ↔ Gross:** Mild correlation (**r = 0.25**) — longer movies tend to perform slightly better.

---

## ⚙️ Tools & Libraries
- **Python** – Data processing and analysis  
- **Pandas / NumPy** – Data manipulation and computation  
- **Seaborn / Matplotlib** – Correlation and trend visualization  

---

## 📂 Files
- `movies.csv` – Source dataset  
- `Movies Analysis and Correlation.ipynb` – Jupyter Notebook with full analysis  

---

## 💡 Summary
This project highlights how **budget and audience engagement** drive box-office success more than critical ratings. It demonstrates **data analysis, visualization, and storytelling** — turning raw movie data into business insights.

---

### 🙌 Acknowledgment
Special thanks to **[Alex The Analyst](https://www.youtube.com/@AlexTheAnalyst)** for his clear and insightful tutorials on Data Analytics, which served as the foundation for this project’s learning and execution.  **[Alex The Analyst GitHub](https://github.com/AlexTheAnalyst)**
