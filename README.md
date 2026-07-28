# 📚 Book Sales Analytics & Bestseller Prediction Using Machine Learning

## 📌 Project Overview

This project demonstrates an end-to-end **Data Analytics and Machine Learning pipeline** using a simulated book sales database.

The project covers:

- SQLite database creation
- ETL data processing
- Exploratory Data Analysis (EDA)
- Data visualization
- Machine learning classification to predict bestseller books

---

## 🎯 Objectives

- Build a relational SQLite database for books and sales
- Extract and transform sales data using Python
- Analyse sales trends and customer purchasing patterns
- Predict potential bestselling books using Machine Learning

---

## 🗄️ Dataset

A synthetic SQLite database was created:

**Database:** `book_sales.db`

Tables:

### Books Table

| Column | Description |
|---|---|
| book_id | Unique book identifier |
| title | Book title |
| author | Author name |
| genre | Book category |

### Sales Table

| Column | Description |
|---|---|
| sale_id | Sales transaction ID |
| book_id | Book reference |
| sale_date | Purchase date |
| quantity | Number of books sold |
| price | Book price |

Generated dataset:

- 10 sample books
- 1,000 sales transactions
- 2023 sales records

---

## 🛠️ Technologies Used

**Programming**
- Python

**Database**
- SQLite

**Data Processing**
- Pandas
- NumPy

**Visualization**
- Matplotlib
- Seaborn

**Machine Learning**
- Scikit-learn
- Random Forest Classifier

**Environment**
- Jupyter Notebook

---

SQLite Database
↓
Extract Data using SQL
↓
Transform Data with Pandas
↓
Calculate Sales Metrics
↓
Export Processed Dataset

## 🔄 ETL Workflow


---

## 📊 Data Visualization

Created visual analysis:

### Monthly Sales by Genre
- Identifies sales trends over time
- Compares genre performance

### Top Authors by Revenue
- Finds highest-performing authors

### Sales Distribution by Genre
- Analyses market share by category

---

## 🤖 Machine Learning Model

### Bestseller Prediction

A **Random Forest Classifier** was trained to predict bestseller status.

Features:

- Genre
- Total quantity sold
- Total revenue

Target:

1 = Bestseller
0 = Non-Bestseller


Bestseller threshold:
Top 20% books by revenue


---

## 📈 Model Evaluation

Performance evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Additional analysis:

- Feature importance ranking
- Bestseller prediction ranking

---

## 🚀 Future Improvements

- Add customer behaviour analysis
- Use real-world book sales datasets
- Implement time-series sales forecasting
- Deploy dashboard using Power BI / Streamlit
- Improve prediction using XGBoost and Neural Networks

---

## 👨‍💻 Author

**M Fadzil Burhan**

Skills Demonstrated:

✅ Python Data Analytics  
✅ SQL Database Management  
✅ ETL Pipeline Development  
✅ Data Visualization  
✅ Machine Learning Classification  
✅ Business Intelligence  




