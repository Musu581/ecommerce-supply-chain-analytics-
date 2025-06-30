# E-Commerce Supply Chain Analytics 📦📊

This project provides end-to-end analysis of e-commerce order and supply chain data, focusing on delivery performance, customer experience, and key operational metrics. It uses Python, Pandas, Matplotlib, Seaborn, and SQL (via SQLite) in a Jupyter Notebook environment.

---

## 📁 Contents

- `E-Commerce Order & Supply Chain Analytics.ipynb` – Main analysis notebook
- Dataset: CSV files (e.g., `orders.csv`, `returns.csv`, `customers.csv`) used for analytics
- `README.md` – Project documentation

---
## 📄 About the Dataset

The dataset used in this project contains information on employees, including:

### 🔹 Personal attributes:
- Age
- Gender
- Education

### 🔹 Professional attributes:
- Department
- Region
- Recruitment Channel

### 🔹 Performance metrics:
- No. of Trainings
- Previous Year Rating
- Awards Won
- Average Training Score

### 🔹 Target variable:
- `is_promoted` (1 if promoted, 0 otherwise — only in `train.csv`)

| File        | Description                         |
|-------------|-------------------------------------|
| `train.csv` | 54,808 records used to train model  |
| `test.csv`  | 23,490 records for prediction       |

---

## 🔍 Objectives

- Analyze **order delivery trends** (on-time vs delayed)
- Identify **key regions and categories** causing delays
- Evaluate **KPIs** like delivery days, shipping mode, sales vs profit
- Provide **insightful visualizations** and **correlation analysis**
- Practice **SQL queries** using pandas & SQLite

---
## 🧰 Technologies Used

- **Languages**: Python
- **Libraries**: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, SQLite
- **Tools**: Jupyter Notebook, SQLite via pandas/sqlite3

---## 📊 Steps Covered

### 1. Data Cleaning
- Handled missing values in `education` and `previous_year_rating`
- Dropped duplicate employee IDs
- Checked for class imbalance in the target variable

### 2. Exploratory Data Analysis (EDA)
- Used statistical summaries (`.describe()`)
- Distribution plots for categorical and numerical variables
- Boxplots and heatmaps to study relationships between features
- SQL queries via `sqlite3` for custom insights (e.g., average age by department)

### 3. Feature Engineering
- One-hot encoding for categorical variables (`gender`, `department`, etc.)
- Aligned test and train columns
- Identified most important features for prediction

### 4. Model Building
- Split data into training and validation sets using `train_test_split`
- Built a `RandomForestClassifier` model
- Evaluated using:
  - ✅ **Accuracy**: 93.47%
  - ✅ Precision, Recall, F1-score
- Visualized top 5 feature importances using a bar chart

---

## 💡 Key Features

- Missing value handling
- Descriptive statistics & distribution analysis
- SQL integration for flexible querying
- Correlation matrix & heatmap
- Visualizations: bar charts, boxplots, and more
- Real business use-case with clean reporting

---

## 📊 Sample KPIs

- Average Delivery Days
- Orders by Region
- Delayed Shipments by Category
- Sales vs Profit by Segment
- SQL-based filtering & grouping insights

---

