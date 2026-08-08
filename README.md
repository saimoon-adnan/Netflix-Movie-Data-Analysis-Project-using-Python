# 🎬 Netflix Movie Data Analysis

A complete end-to-end data analysis project exploring trends in Netflix movies using **Python** and **Pandas**. The project performs ETL (Extract, Transform, Load) operations on a raw dataset of **9,000+ movies**, cleans and transforms the data, and derives actionable insights through exploratory data analysis (EDA) and visualization.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-informational)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-lightgrey)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-yellow)

---

## 📌 Project Objective

The main objective of this project is to analyze Netflix movie trends and answer real-world business questions using data analysis techniques on a dataset of 9,000+ movies.

---

## ❓ Business Problems Solved

- What is the most frequent movie genre on Netflix?
- Which movie has the highest vote average?
- Which movie has the highest popularity, and what genre does it belong to?
- Which movie has the lowest popularity, and what genre does it belong to?
- Which year had the highest number of released movies?

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Core programming language |
| **Pandas** | Data manipulation and cleaning |
| **NumPy** | Numerical computations |
| **Matplotlib** | Data visualization |
| **Jupyter Notebook** | Interactive development environment |

---

## 🔄 ETL Process

**Extract**
- Loaded the raw Netflix dataset using Pandas.

**Transform**
- Removed duplicate values
- Handled missing data
- Converted release date format
- Split and cleaned genre values
- Categorized vote averages
- Removed unnecessary columns

**Load**
- Prepared a clean, analysis-ready dataset for visualization and insight generation.

---

## 🧹 Data Cleaning Process

Several preprocessing techniques were applied before analysis, including handling null values, formatting columns, splitting multi-value genre fields, and transforming numerical data to improve analysis accuracy.

---

## 📊 About the Dataset

The dataset contains information about Netflix movies, including:

- Movie Title
- Genre
- Popularity
- Vote Average
- Release Date
- Language
- Other movie-related attributes

---

## 💡 Key Insights

- **Drama** was one of the most frequent movie genres on Netflix.
- Certain years showed a significant increase in movie releases.
- Highly popular movies do not always receive the highest vote averages.
- Data visualization helped uncover trends and audience preferences that raw data alone did not reveal.

---

## 📈 Project Visualizations

| Release Date Distribution | Vote Distribution | Genre Distribution |
|:---:|:---:|:---:|
| *(chart)* | *(chart)* | *(chart)* |

> Add your chart images here (e.g. `images/release_date_distribution.png`, `images/vote_distribution.png`, `images/genre_distribution.png`) and update the links above.

---

## 🚀 How to Run This Project

1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
2. Install the required dependencies
   ```bash
   pip install pandas numpy matplotlib jupyter
   ```
3. Launch Jupyter Notebook
   ```bash
   jupyter notebook
   ```
4. Open the `.ipynb` file and run the cells sequentially.

---

## ✅ Conclusion

This project demonstrates practical skills in Python-based data analysis, ETL processing, and data visualization. It highlights the ability to transform raw, messy data into clean datasets and translate that data into meaningful, business-relevant insights.

---

## 👤 Author

**Saimoon Ahmed Adnan**
Computer Science student focused on product analytics, data science, machine learning, and software engineering.

- 📧 Email: adnansaimoon@gmail.com

