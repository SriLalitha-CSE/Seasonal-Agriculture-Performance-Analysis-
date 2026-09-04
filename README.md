# Seasonal Agriculture Performance Analysis

## 📌 Overview

This project analyzes farm-level agricultural data across three Indian cropping seasons — **Kharif, Rabi, and Zaid** — to uncover seasonal patterns, trends, and relationships in crop yield, resource usage, environmental conditions, and economic performance. The goal is to support evidence-based, season-specific agricultural planning.

## 📊 Dataset

- **4,000 farm-level records**
- **8 Indian states**, **8 crops**, **3 seasons** (Kharif, Rabi, Zaid)
- Features include:
  - **Environmental conditions**: rainfall, temperature, humidity, soil pH, soil moisture, sunlight hours
  - **Resource usage**: water, fertilizer (N/P/K), pesticide, irrigation method
  - **Economic outcomes**: cost, revenue, profit
  - **Yield & production**: yield (t/ha), production volume

File: `seasonal_agriculture_performance_dataset.csv`

## 🎯 Objectives

- Clean and prepare the seasonal agriculture dataset
- Examine how yield, cost, and profit vary across seasons
- Identify seasonal patterns and relationships using statistical testing (ANOVA, correlation)
- Compare performance across crops, states, and irrigation methods
- Derive evidence-based conclusions and recommendations for seasonal agricultural planning

## 🛠️ Technology Used

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas & NumPy | Data cleaning, transformation, numerical computation |
| Matplotlib & Seaborn | Statistical charts, boxplots, heatmaps |
| SciPy | ANOVA and correlation significance testing |
| Jupyter Notebook | End-to-end documentation of the analysis |

## 📁 Repository Structure

```
├── README.md
├── Seasonal_Agriculture_Performance_Analysis.ipynb   # Full analysis notebook
├── seasonal_agriculture_performance_dataset.csv       # Raw dataset
└── Seasonal_Agriculture_Performance_Analysis_Presentation.pptx   # Project presentation slides
```

## 🔑 Key Findings

- **Kharif** records the highest average yield (5.64 t/ha) and is the most profitable season (avg ₹1,78,915; 57.8% of farms profitable).
- **Zaid** records the lowest yield (4.67 t/ha) and runs a net loss on average (-₹24,805; only 35.5% of farms profitable).
- Seasonal differences in yield, profit, and rainfall are all **statistically significant** (one-way ANOVA, p < 0.05).
- Yield correlates most strongly with water usage (r ≈ 0.39); disease/pest risk rises sharply with rainfall and humidity (r ≈ 0.6).
- Sugarcane shows the largest seasonal swing in yield; most states perform best in Kharif, confirming the seasonal effect holds consistently across crops and regions.

## 🚀 How to Run

1. Clone this repository
   ```bash
   git clone <your-repo-url>
   cd <repo-folder>
   ```
2. Install dependencies
   ```bash
   pip install pandas numpy matplotlib seaborn scipy jupyter
   ```
3. Launch the notebook
   ```bash
   jupyter notebook Seasonal_Agriculture_Performance_Analysis.ipynb
   ```
4. Run all cells to reproduce the analysis (the dataset CSV must be in the same folder).

## 📈 Recommendations

- Expand water-efficient irrigation (drip/sprinkler) in Zaid-season farms
- Reassess crop selection for Zaid season toward more resilient, less water-intensive crops
- Target disease/pest management support for Zaid-season and extreme-loss-prone farms
- Extend the analysis with multi-year data to separate genuine seasonal effects from weather anomalies

## 👤 Author

- **Name:** PURRU.SRILALITHA SAI PRASANNA


