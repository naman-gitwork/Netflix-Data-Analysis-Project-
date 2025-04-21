# 📊 Netflix EDA Project

This repository contains an Exploratory Data Analysis (EDA) on a Netflix dataset. The aim is to uncover insights into the content available on Netflix, identify trends, clean the data for further use, and visualize key metrics such as genre distribution, release patterns, and popularity of content.

---

## 🔍 Project Overview

- **Dataset Shape**: 9827 rows × 9 columns
- **Objective**: Perform EDA to understand patterns and clean the dataset for future modeling or dashboarding.
- **Key Steps Covered**:
  - Data Cleaning & Preprocessing
  - Handling Duplicates & Missing Values
  - Outlier Detection (Popularity)
  - Feature Engineering on Date and Genre Columns
  - Visual Analysis using Seaborn and Matplotlib

---

## 🧹 Data Cleaning Highlights

- Converted `release_date` to `datetime` for year extraction
- Dropped irrelevant columns: `overview`, `original_language`, `poster_url`
- Cleaned `genre` column (comma-separated values with wide spacing)
- Checked for and removed duplicates
- Handled outliers in the `popularity` column

---

## 📊 Visual Insights

- Year-wise content distribution
- Genre frequency & popularity trends
- Popularity analysis and outlier behavior
- Content production trends over the years

---

## 📁 Files Included

- `Netflix EDA .ipynb`: The complete Jupyter Notebook with code, output, and visualizations.
- `README.md`: This documentation file.

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib

---

## 💡 Key Learnings

- Importance of preprocessing text-heavy and multi-category columns
- Outlier handling and its impact on distribution-based visualizations
- Creating visually meaningful plots to explain trends

---

## 📬 Contact

For queries or collaboration, feel free to connect:

- 📧 namanmittal3015@gmail.com
- 🌐 [LinkedIn](https://www.linkedin.com/in/naman-mittal-73977b24a)
- 📁 [Portfolio](https://my.newtonschool.co/user/namanmittal3015)

---

⭐ If you found this analysis helpful, consider giving a star to this repo!
