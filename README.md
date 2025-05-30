# 🛒 SQL Ecommerce Project

This project is a comprehensive analysis of ecommerce business operations using **SQL** and **Python**. It involves importing CSV data from a Kaggle dataset into MySQL, executing a series of basic to advanced SQL queries, and visualizing insights using Python libraries such as `pandas`, `numpy`, `matplotlib`, and `seaborn`.

---

## 📦 Dataset

- **Source:** [Kaggle - Target Dataset](https://www.kaggle.com/datasets/devarajv88/target-dataset?select=products.csv)
- Files used:
  - `customers.csv`
  - `orders.csv`
  - `order_items.csv`
  - `payments.csv`
  - `products.csv`
  - `sellers.csv`
  - `geolocation.csv`

---

## 💻 Technologies Used

- **SQL / MySQL** — query logic and data modeling  
- **Python** — data transformation and visualization  
- **pandas** — data manipulation  
- **numpy** — correlation and numerical operations  
- **matplotlib** & **seaborn** — data visualization  
- **mysql-connector-python** — connecting Python with MySQL  

---

## 🛠 Installation & Setup

1. **Install dependencies:**

```bash
pip install pandas numpy matplotlib seaborn mysql-connector-python
```

2. **Set up MySQL database:**

```bash
Create a database named ecommerce

Update your MySQL credentials in the Python script
```

3. **Convert CSV to MySQL:**

- A custom Python script was used to:

  - Read each CSV file using pandas

  - Clean and infer schema types

  - Create corresponding MySQL tables

  - Insert data row-by-row into MySQL

```bash
🔧 Script: CSV_To_SQL.ipynb
```

---

## 🔍 SQL Query Tiers

- ✅ Basic Queries
  - List all unique cities where customers are located

  - Count number of orders placed in 2017

  - Total sales per product category

  - Percentage of orders paid in installments

  - Count customers by state (visualized in bar chart)

- ⚙️ Intermediate Queries
  - Monthly order count in 2018 (visualized using seaborn)

  - Avg. products per order grouped by city

  - Revenue contribution by each category (in %)

  - Correlation between price and purchase frequency (using np.corrcoef)

  - Revenue per seller, ranked and visualized in bar chart

- 🧠 Advanced Queries
  - Moving average of customer order values

  - Monthly cumulative sales per year

  - Year-over-Year sales growth (%)

  - Retention rate: % of customers who made another purchase within 6 months

  - Top 3 customers by spending per year (visualized in a grouped bar chart)

---

## 📁 Project Structure

```bash
SQL-Ecommerce-Project/
├── csv_to_sql_loader.py         # CSV-to-SQL conversion script
├── sql_queries.py               # SQL queries with Python integration
├── screenshots/                 # Plots and visualizations
├── dataset/                     # Raw Kaggle CSVs
├── notebooks/                   # Optional Jupyter analysis notebooks
└── README.md                    # Project documentation

```

---

## 🚀 Future Enhancements

✅ Add Streamlit dashboard for interactive visualization

📦 Automate pipeline using Airflow

📊 Export results to Excel/CSV reports

🧠 Integrate predictive modeling on customer behavior

---

⭐ If you found this project helpful, give it a star and share it with your network!


---

### ✅ What You Should Do:
- Add screenshots from your project to a `screenshots/` folder and update image paths.
- Replace `your.email@example.com` and GitHub/LinkedIn links with your info.
- Upload all relevant Python scripts and SQL files.
- Rename the repo to something like `sql-ecommerce-analysis`.

Let me know if you'd like a `.ipynb` version of this analysis or want to turn it into a Streamlit app!







