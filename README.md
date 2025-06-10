# Extrovert vs Introvert Behavior Analysis

This project analyzes the behavioral differences between extroverted and introverted individuals using the publicly available dataset **"Extrovert vs Introvert Behavior Data"** from Kaggle. The goal is to explore patterns and relationships that characterize both personality types.

---

## 📌 Project Overview

The analysis follows the classic data analysis process:

- **Ask:** Define key questions and analysis objectives.
- **Prepare:** Assess dataset quality and understand its structure.
- **Process:** Clean and transform data to ensure consistency.
- **Analyze:** Identify patterns, calculate statistics, and perform correlations.
- **Share:** Create clear visualizations to communicate findings.
- **Act:** Reflect on results and their potential applications.

---

## ❓ Key Questions

- What factors determine if a person is extroverted or introverted?
- What relationships exist between social behavior variables?

---

## 📊 About the Dataset

- **Source:** Kaggle  
- **Author:** [rakeshkapilavai](https://www.kaggle.com/datasets/rakeshkapilavai/extrovert-vs-introvert-behavior-data)  
- **Rows:** 2,900  
- **Columns:** 8  
- **Last Updated:** May 21, 2025

### Main Variables:

| Column                  | Description                                   |
|-------------------------|-----------------------------------------------|
| Time_spent_Alone        | Daily hours spent alone (0–11)                 |
| Stage_fear              | Stage fright (Yes/No)                          |
| Social_event_attendance | Frequency of attending social events (0–10)  |
| Going_outside           | Frequency of going outside (0–7)               |
| Drained_after_socializing | Feeling drained after socializing (Yes/No)  |
| Friends_circle_size     | Number of close friends (0–15)                 |
| Post_frequency          | Frequency of social media posts (0–10)        |
| Personality             | Personality type (Extrovert / Introvert)      |

---

## 🧹 Data Cleaning and Processing

- Rows with multiple missing values were removed.
- Formats were standardized, and categorical variables were converted to numerical.
- The final dataset contains **2,868 rows** ready for analysis.

---

## 🔍 Analysis and Results

Key points from the analysis include:

- Extroverts tend to have larger friend circles, attend more social events, and post more on social media.
- Introverts show a higher association with stage fright and feeling drained after socializing.
- Strong correlations were found between key variables such as:
  - `Stage_fear` and `Personality`: **-0.86**
  - `Drained_after_socializing` and `Personality`: **-0.87**
  - `Social_event_attendance` and `Personality`: **0.73**

---

## 📈 Visualizations

Included in the project are pie charts and bar graphs showing:

- Distribution of personality types
- Comparison of variables by personality type
- Relationships between key social behavior variables

---

## 📎 Resources

- 📂 [Notebook on Kaggle](https://www.kaggle.com/code/diegorossprice/extrovert-vs-introvert)
- 📥 Original Dataset: [Kaggle Dataset](https://www.kaggle.com/datasets/rakeshkapilavai/extrovert-vs-introvert-behavior-data)

---

## 🛠️ Tools Used

- Python (Pandas, Seaborn, Matplotlib)
- Kaggle Notebooks
- GitHub

---

## 🧑‍💻 Author

Diego Ross – Data Analysis
