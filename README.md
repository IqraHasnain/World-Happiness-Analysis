# World Happiness Analysis 2015-2022

An end-to-end exploratory data analysis and statistical study of global happiness across 147–158 countries from 2015 to 2022, combining 8 years of data to uncover trends, correlations, and regional patterns.

## 🗂️ Dataset

- Coverage: 2015–2022
- 147–158 countries per year
- 1,231 total records after combining

--

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| NumPy | numerical computing |
| Pandas | Data manipulation & analysis |
| Matplotlib & Seaborn | Data visualization |
| Scipy | Statistical analysis |
| Jupyter Notebook | Interactive development environment |

--

## 📊 Analysis performed

- Identified top/bottom 10 happiest countries and regions
- Correlation analysis between GDP, Health, Freedom and Happiness Score
- T-test comparing Western Europe vs Sub-Saharan Africa happiness scores
- Multi-year trend analysis across 1,231 records spanning 2015–2022 (trend analysis limited to 2015–2021 due to incomplete 2022 data)

--

## 🔍 Key Insights

- **Western Europe** had the highest median happiness score across regions based on the 2015 boxplot analysis, while **Australia and New Zealand** had the highest average score but only includes 2 countries.
- Correlation between GDP and Happiness is **0.78** — it means Richest Countries tend to have happier citizens however this does not mean wealth causes happiness.
- **Iceland and Denmark** each appeared in the top 5 happiest countries across all 7 years with valid happiness data (2015-2021), as 2022 lacked complete score data.
- **Western Europe and Sub-Saharan Africa** have statistically significantly different happiness scores **(t-stat = 13.37, p-value ≈ 0)**, confirming the happiness gap between these regions is not due to chance.
- Global happiness between 2015-2021 — increased from **5.37 in 2015 to 5.53 in 2021** — a modest but consistent upward trend suggesting gradual improvement in global wellbeing despite economic and political challenges.

--

## 📁 Project Structure

```
World-Happiness-Analysis/
│
├── Dataset/                        # Raw dataset files
├── World_Happiness_Analysis.ipynb  # Main analysis notebook
└── README.md
```

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/IqraHasnain/World-Happiness-Analysis.git
   ```
2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/mathurinache/world-happiness-report) and place files in the `Dataset/` folder
3. Install required libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn scipy
   ```
4. Open and run `World-Happiness-Analysis.ipynb` in Jupyter Notebook

---

## 👩‍💻 Author

**Iqra Hasnain** — Aspiring Data Scientist  
[GitHub](https://github.com/IqraHasnain)
[LinkedIn](https://www.linkedin.com/in/iqra-hasnain-68a357282/)
