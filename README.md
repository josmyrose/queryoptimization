# 🚖 Benchmarking SQL Queries: Pandas vs DuckDB

This project explores the performance and efficiency of running SQL-like queries on large datasets using two popular Python tools: **pandas** and **DuckDB**.

## 🔍 Objective

To compare:
- Query execution speed
- Memory usage
- Code simplicity and readability

...when performing operations like filtering, grouping, joining, and aggregating data from the NYC Taxi dataset.

## 📂 Dataset

- **Source:** NYC Yellow Taxi Trip Records
- **Format:** Parquet
- **Size:** ~1.7GB+

## 🛠️ Tech Stack

- Python
- Pandas
- DuckDB
- Google Colab

## 📊 Key Findings

- DuckDB significantly outperforms pandas for large dataset queries, especially with complex SQL operations.
- Pandas remains intuitive but less memory-efficient.
- DuckDB offers SQL syntax directly on Parquet files without loading everything into memory.

## 🧠 Ideal For

- Data scientists and analysts working with large datasets
- Students and educators exploring database engines in Python
- Anyone comparing data processing tools for performance tuning

## 🚀 Run the Notebook

Try it live in Google Colab 👉 [Open in Colab](https://colab.research.google.com/drive/1xmc8m6Pkqx8reDYZvuf1aJgZH2j205eC?authuser=1#scrollTo=Jd4BO4irA8No)

---

Feel free to clone, contribute, or suggest improvements!
