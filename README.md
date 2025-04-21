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
- Conclusion
QI: What is the most frequent genre in the dataset?
Drama genre is the most frequent genre in our dataset and has appeared more than 14% of the times among 19 other genres.
Q2: What genres has highest votes?
we have 25.5% of our dataset with popular vote (652e rows). Drama again gets the highest popularity among fans by being having more than 18.5% of movies popularities .
Q3: What movie got the highest popularity? what's its genre?
Spider-Man: No Way Home has the highest popularity rate in our dataset and it has genres of Action, Adventure and Sience Fiction.
Q4: What movie got the lowest popularity? what's its genre?
The united states, thread' has the highest lowest rate in our dataset and it has genres of music, drama,'war',' sci-fi.
Q4: Which year has the most filmmed movies?'
year 2021 has the highest filmming rate in our dataset.

---

## 📬 Contact

For queries or collaboration, feel free to connect:

- 📧 namanmittal3015@gmail.com
- 🌐 [LinkedIn](https://www.linkedin.com/in/naman-mittal-73977b24a)
- 📁 [Portfolio](https://my.newtonschool.co/user/namanmittal3015)

---

⭐ If you found this analysis helpful, consider giving a star to this repo!
