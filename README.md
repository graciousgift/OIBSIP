# OIBSIP
Oasis Infobyte Data Science Internship Projects

## 👤 Intern Details
- **Name:** Gift Lawrence
- **Task:** Task 1 — Iris Flower Classification
- **Organization:** Oasis Infobyte
- **Domain:** Data Science & Machine Learning
- 
# Task_1: Iris Flower Classification

# 🌸 Iris Flower Classification — OASIS INFOBYTE Data Science Internship
A beginner-friendly machine learning project that classifies Iris flower species using physical measurements. Built with Python and scikit-learn.


---

.

📌 Project Description
The goal of this project is to train a classification model that can identify the species of an Iris flower — setosa, versicolor, or virginica — based on four measurements:

Sepal Length (cm)
Sepal Width (cm)
Petal Length (cm)
Petal Width (cm)

The dataset contains 150 flowers (50 per species) with no missing values.
.

🚀 Live Demo

(https://colab.research.google.com/drive/1YFALH4-svF4I2ylhTS4vrZK3kiO5biXe?usp=sharing)

Click the link above to run the notebook instantly in your browser — no installation required.


---

.


📁 Project Structure
OIBSIP/
│
├── iris_classification_clean.ipynb   ← Main notebook (start here)
├── Iris.csv                          ← Dataset
└── README.md                         ← This file

🛠️ Tools & Libraries
ToolPurposePython 3.10Programming languagepandasData loading and manipulationnumpyNumerical operationsmatplotlib / seabornData visualisationscikit-learnMachine learning (Random Forest, evaluation)

📊 What the Notebook Covers
StepDescription
1 Import libraries
2 Load dataset and view data structure
3 Exploratory Data Analysis (pairplot, heatmap, boxplot)
4 Prepare data (encode labels, train/test split)
5 Train a Random Forest Classifier
6Evaluate with accuracy score and classification report
7 Feature importance chart
8 Predict a new flower's species
9 Cross-validation for more reliable accuracy
10 Learning curve to detect overfitting/underfitting

📈 Results

Test Accuracy: ~96–100% depending on split
Cross-Validation Mean: consistent across all 5 folds
Strongest features: PetalLengthCm and PetalWidthCm
Hardest case: slight overlap between versicolor and virginica


▶️ How to Run Locally
bash# 1. Clone this repository
git clone https://github.com/graciousgift/OIBSIP.git
cd OIBSIP

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

# 3. Launch the notebook
jupyter notebook iris_classification_clean.ipynb
Or just use the Colab badge above — no setup needed.

🙋 About
This project was completed as part of the OASIS Infobyte Internship Programme (Machine Learning Track).
Author: Graciousgift
GitHub: @graciousgift
## 📎 Links
- 🔗 GitHub Repository: https://github.com/graciousgift/OIBSIP
- 🎯 Live Demo: https://colab.research.google.com/drive/1YFALH4-svF4I2ylhTS4vrZK3kiO5biXe?usp=sharing
- 🏢 Oasis Infobyte: https://oasisinfobyte.com

# Task_2: Employment Analysis

# 📉 Unemployment Analysis with Python
### OIBSIP Data Science Internship — Task 2

## 📌 Project Overview

This project analyzes unemployment trends in India, with a particular focus on how the **COVID-19 pandemic and lockdown** dramatically impacted the unemployment rate across different states. Using Python's data analysis and visualization libraries, the notebook uncovers regional patterns, temporal trends, and the relationship between employment indicators.

> **Key Question:** How did COVID-19 lockdowns affect unemployment across Indian states, and which regions were hit hardest?


---

## 📂 Repository Structure

```
OIBSIP/
│
├── Gift_Lawrence_Task2.ipynb      # Main analysis notebook
├── Unemployment_Rate_upto_11_2020.csv  # Dataset (unemployment by state, monthly)
└── README.md                      # This file
```

---

## 📊 Dataset

**Source:** [CMIE — Centre for Monitoring Indian Economy](https://unemploymentinindia.cmie.com/)

| Column | Description |
|--------|-------------|
| `Region` | Indian state name |
| `Date` | Date of observation (monthly) |
| `Frequency` | Measurement frequency (Monthly) |
| `Estimated Unemployment Rate (%)` | % of labour force unemployed |
| `Estimated Employed` | Number of employed individuals |
| `Estimated Labour Participation Rate (%)` | % of eligible population actively in the workforce |

The dataset covers unemployment data up to **November 2020**, capturing the full arc of India's COVID-19 first wave.

---

## 🔍 Analysis Performed

### 1. Data Loading & Exploration
- Imported and inspected dataset shape, data types, and missing values
- Parsed date columns and set up temporal indexing

### 2. Exploratory Data Analysis (EDA)
- **Descriptive statistics** — mean, median, and spread of unemployment rate by region
- **Correlation analysis** — relationship between unemployment rate, employment, and labour participation

### 3. Data Visualizations
- 📈 **Time-series plots** — unemployment rate trend before and after lockdown (March 2020)
- 🗺️ **Regional bar charts** — states with highest/lowest unemployment
- 🔥 **Heatmaps** — correlation matrix between key indicators
- 📦 **Box plots** — distribution of unemployment across states
- 🔵 **Scatter plots** — employment vs. labour participation rate

### 4. Key Insights
- Spike in national unemployment rate during April–May 2020 (peak lockdown)
- States like **Tripura, Haryana, and Himachal Pradesh** saw the sharpest increases
- Southern states generally showed higher labour participation rates
- Strong negative correlation between unemployment rate and estimated employed

---

## 🛠️ Technologies Used

| Library | Purpose |
|---------|---------|
| `pandas` | Data loading, cleaning, and manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Base plotting |
| `seaborn` | Statistical visualizations |
| `plotly` | Interactive charts (if applicable) |

---

## ▶️ How to Run

### Prerequisites

Ensure you have Python 3.8+ and Jupyter installed.

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/graciousgift/OIBSIP.git
   cd OIBSIP
   ```

2. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook Gift_Lawrence_Task2.ipynb
   ```

3. **Run all cells** from top to bottom (`Kernel → Restart & Run All`).

---

## 📈 Sample Findings

- 🔺 India's average unemployment rate **surged from ~7% to over 23%** during April 2020
- 🌍 Urban areas experienced more severe unemployment spikes than rural counterparts
- 📉 Labour participation rate **declined** as workers dropped out of the job search entirely
- ♻️ Recovery began in June 2020, though rates remained elevated above pre-COVID baselines

---

## 🤝 Acknowledgements

- **Oasis Infobyte** — for the internship opportunity and project framework
- **CMIE** — for the publicly available unemployment dataset
- The open-source Python data science community

---

## 👩‍💻 Author

**Gift Lawrence**
- GitHub: [@graciousgift](https://github.com/graciousgift)
- Project: Oasis Infobyte Data Science Internship (OIBSIP)

---

*This project was completed as part of the Oasis Infobyte Data Science Internship Program.*
