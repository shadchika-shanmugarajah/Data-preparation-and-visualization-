# 📊 Netflix Movie & TV Show Data Analysis

This project is a **data analysis and visualization** of Netflix's movie and TV show catalog. The dataset was sourced from **Kaggle** and includes detailed information such as title, release year, genre, cast, duration, and rating.

---

## 📥 Dataset Source

- **Source**: [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- The dataset includes movies and TV shows available on Netflix till the time of collection.

---

## 🧹 Data Preprocessing

In the data preprocessing step, I:

- Loaded the dataset using **pandas**
- Dropped unnecessary columns that were not useful for the analysis (e.g., `show_id`, `description`)
- Handled missing values and date conversions (like parsing `release_year` correctly)
- Replaced the values in the **`rating`** column:
  - `PG-13` → `Average`
  - `TV-MA` → `Good`
  - (and similar replacements for clarity)

---

## 🐍 Python Libraries Used

| Library      | Purpose |
|--------------|---------|
| **pandas**   | For reading, cleaning, and manipulating the dataset |
| **numpy**    | Used for numerical operations and handling arrays |
| **matplotlib** | For creating visualizations and plots |
| **seaborn**  | For creating attractive and informative statistical graphics |

---

## 📒 Jupyter Notebook

This project was built in **Jupyter Notebook**, which is great for combining code, output, and markdown in one place — perfect for exploratory data analysis and interactive visualization.

---

## 📈 Visualizations & Graphs

A variety of plots were created to understand the data better:

- **Countplot** for distribution of genres (`listed_in`)
- **Barplot** showing top 10 most common genres
- **Line plot** to show trends in movie releases over the years
- **Pie/Donut charts** for top 5 genre share
- **Heatmap** to identify correlation between numerical columns
- **Boxplot** and **stripplot** to explore relationships between rating and duration (if applicable)

These visualizations help uncover patterns in Netflix's content, such as which genres are most popular, how content is distributed across years, and how ratings relate to content type.

---

## 🚀 How to Run

1. Clone this repo or download the notebook.
2. Open the `.ipynb` file in **Jupyter Notebook** or **JupyterLab**
3. Run the cells step-by-step to see data cleaning and visualization.

---

## ✅ Outcome

Through this project, we gained insights into:

- Most frequent genres on Netflix
- Trends in movie releases over time
- How ratings were distributed and reclassified
- Visual storytelling using Python libraries

---

Feel free to contribute or fork this repo for your own Netflix data experiments!


