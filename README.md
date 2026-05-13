# Retail Sales & Market Analysis

## 📌 Project Overview
This project focuses on analyzing Walmart retail sales data to uncover sales trends, seasonal demand patterns, store performance insights, and market behavior. The objective is to generate actionable business insights that support data-driven sales optimization and strategic decision-making.

---

## 📊 Visual Analysis & Dashboards

### 📈 Sales Trends & Distribution
Identifying growth patterns and how sales are distributed across the timeline and different store segments.

| Monthly Sales Trends | Store-wise Sales Distribution |
|---|---|
| ![Monthly Sales](https://raw.githubusercontent.com/ThotakuraJayanth/Retail-Sales-and-Market-Analysis/main/Chart1.png) | ![Store Sales Distribution](https://raw.githubusercontent.com/ThotakuraJayanth/Retail-Sales-and-Market-Analysis/main/Chart%204.png) |

### 🔍 Market Factors & Weekly Analysis
Analyzing how external factors like CPI and Unemployment correlate with sales, and observing weekly fluctuations.

| Correlation Heatmap | Weekly Sales Analysis |
|---|---|
| ![Heatmap](https://raw.githubusercontent.com/ThotakuraJayanth/Retail-Sales-and-Market-Analysis/main/Chart%203.png) | ![Weekly Sales](https://raw.githubusercontent.com/ThotakuraJayanth/Retail-Sales-and-Market-Analysis/main/Chart2.png) |

> **Analysis Highlight:** The chart below specifically illustrates the significant impact of holiday periods on total revenue compared to non-holiday weeks.
> ![Holiday Impact](https://raw.githubusercontent.com/ThotakuraJayanth/Retail-Sales-and-Market-Analysis/main/Chart%205.png)

---

## ⚠️ Business Problem
Retail businesses generate large volumes of sales data, but identifying meaningful patterns for revenue growth can be challenging. This project analyzes sales behavior, seasonal impacts, and store performance to support better business strategy.

## 📂 Dataset Information
* **Dataset:** [Walmart Retail Sales Dataset](cleaned_walmart_sales_data.csv)
* **Features:** Store ID, Date, Weekly Sales, Holiday Flag, Temperature, Fuel Price, CPI, Unemployment.

## 🛠️ Tools & Technologies
* **Python** (Pandas, NumPy)
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## 💡 Key Findings
* **Seasonal Peaks:** Sales show clear spikes during holiday periods compared to regular business weeks.
* **Store Variation:** Significant performance gaps exist between Store IDs, suggesting specific stores have better local market capture.
* **Economic Indicators:** Factors like CPI and Fuel Prices show a measurable correlation with shifting consumer spending habits.

## 🚀 Business Recommendations
* **Inventory Management:** Increase stock levels 2-3 weeks prior to identified seasonal peak months.
* **Targeted Marketing:** Focus promotional budgets on high-performing stores to maximize ROI.
* **Economic Forecasting:** Use CPI and Unemployment trends to adjust sales targets for the upcoming quarters.

## 📁 Project Structure
```bash
Retail-Sales-Market-Analysis/
│
├── cleaned_walmart_sales_data.csv        # Processed Dataset
├── Retail_Sales_and_Market_Analysis.ipynb # Full Python Analysis
├── Chart1.png, Chart2.png...             # Visualizations
└── README.md                             # Documentation
