# 🎵 Spotify Track Analysis: Foundations of Data Science Capstone

[![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-orange.svg)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green.svg)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-blue.svg)](https://seaborn.org/)

## 📝 Project Overview
This project is a comprehensive data analysis of the Spotify dataset, completed as part of the **Foundations of Data Science** capstone. We explore the relationship between audio features (energy, loudness, danceability) and track popularity across various genres.

**Goal:** To transform raw, noisy data into actionable business insights for record labels and music streaming platforms.

---

## 👥 Group Members
* **Member 1:** Aayush /[AayushCode24-7]
* **Member 2:** Aditya /[adityasyntaxerror]
* **Member 3:** Sanskar/[sanskarpatil2716-prog]

---

## 📊 Project Workflow
We followed a systematic Data Science lifecycle:

1.  **Data Understanding:** Inspected 114,000+ records to identify features, data types, and potential structural issues.
2.  **Data Wrangling:**
    * Removed redundant index columns.
    * Eliminated ~24k duplicate track IDs to ensure statistical integrity.
    * Handled missing values to maintain clean dataset quality.
    * Engineered a `duration_min` feature for better readability.
3.  **Visualization:** Conducted exploratory data analysis (EDA) using five mandatory plot types: Bar, Pie, Histogram, Scatter, and Box Plots.
4.  **Insight Generation:** Derived practical conclusions from trends in genre popularity and audio feature correlations.

---

## 💡 Key Insights & Business Recommendations

* **Genre Popularity:** Genres such as K-pop and Pop-film currently dominate in average popularity, suggesting a shift toward high-production, visually-oriented music.
* **Content Strategy:** While only 8.6% of the library is explicit, these tracks maintain a higher median popularity, indicating that "Parental Advisory" labels do not discourage listener engagement.
* **Audio Optimization:** A strong positive correlation exists between *Loudness* and *Energy*. For new releases aiming for high popularity, producers should target a loudness range of -7dB to -5dB and energy levels above 0.6.

---

## 🛠 Technologies Used
* **Language:** Python 3.x
* **Libraries:** * `Pandas`: For data manipulation and cleaning.
    * `Matplotlib`: For generating the core visualizations.
    * `Seaborn`: For advanced statistical plotting.
* **Environment:** Jupyter Notebook / Google Colab

---

## 🚀 How to Run
1.  Ensure you have the required libraries installed:
    ```bash
    pip install pandas matplotlib seaborn
    ```
2.  Place the `dataset.csv` file in the same directory as the `.ipynb` notebook.
3.  Run the notebook cells in sequential order (`Kernel` -> `Restart & Run All`).

---

## 📂 Deliverables
* **Jupyter Notebook:** `Foundations_of_DS_Capstone.ipynb` (Clean, commented code)
* **Business Report:** `Capstone_Business_Report.pdf`
* **Presentation:** `Project_Presentation.pptx`

---
*Created for the Foundations of Data Science Course - April 2026*
