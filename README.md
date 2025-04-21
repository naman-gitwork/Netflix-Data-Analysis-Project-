# 📊 Netflix EDA Project

This repository contains an Exploratory Data Analysis (EDA) on a Netflix dataset. The objective of this project is to uncover insights into Netflix content, identify trends, clean the data for future use, and visualize key metrics like genre distribution, release patterns, and content popularity.

---

## 🔍 Project Overview

**Dataset Shape:** 9827 rows × 9 columns  
**Objective:** Perform EDA to understand patterns and clean the dataset for future modeling or dashboarding.

---

## Key Steps Covered:
- **Data Cleaning & Preprocessing**
  - Handling duplicates and missing values.
  - Outlier detection (particularly in popularity).
  - Feature engineering on date and genre columns.

- **Visual Analysis:**
  - Visualizing key metrics such as genre distribution, popularity trends, and production over time.

---

## 🧹 Data Cleaning Highlights:
- **Date Handling:** Converted `release_date` to a datetime format for year extraction.
- **Column Cleaning:** Dropped irrelevant columns like `overview`, `original_language`, and `poster_url`.
- **Genre Column:** Cleaned up genre column (comma-separated values with extra spaces).
- **Duplicates & Outliers:** Checked for and removed duplicates, handled outliers in the popularity column.

---

## 📊 Visual Insights:
- **Year-wise Content Distribution:** Trends in Netflix content over the years.
- **Genre Frequency & Popularity Trends:** Analysis of which genres are most frequent and how their popularity evolves.
- **Popularity Analysis & Outliers:** Investigating the impact of outliers on content popularity.
- **Content Production Trends:** How content production has evolved over time.

---

## 📁 Files Included:
- **Netflix EDA .ipynb:** Complete Jupyter Notebook with code, output, and visualizations.
- **README.md:** Documentation file (this one).

---

## 🛠️ Tools Used:
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib

---

## 💡 Key Learnings:
- **Preprocessing:** Importance of cleaning text-heavy and multi-category columns.
- **Outlier Handling:** Impact on distribution-based visualizations.
- **Visualization Techniques:** How to create visually meaningful plots that explain trends clearly.

---

## Conclusion:

1. **What is the most frequent genre in the dataset?**
   - Drama is the most frequent genre, appearing in over 14% of the dataset.
   
2. **What genre has the highest number of votes?**
   - Drama again dominates in popularity, accounting for more than 18.5% of the total popularity votes.

3. **Which movie has the highest popularity?**
   - *Spider-Man: No Way Home* holds the highest popularity, with genres including Action, Adventure, and Science Fiction.

4. **Which movie has the lowest popularity?**
   - *The United States vs. Billie Holiday* has the lowest popularity, with genres such as Music, Drama, War, and Sci-Fi.

5. **Which year has the most films produced?**
   - 2021 saw the highest number of movies produced in the dataset.

---

## 📬 Contact:
For queries or collaboration, feel free to connect:

- **Email:** namanmittal3015@gmail.com  
- **LinkedIn:** [Naman Mittal LinkedIn](https://www.linkedin.com/in/naman-mittal-73977b24a/)  
- **Portfolio:** [https://my.newtonschool.co/user/namanmittal3015](https://my.newtonschool.co/user/namanmittal3015)

⭐ If you found this analysis helpful, consider giving a star to this repository!
