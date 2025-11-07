# Data Science Internship Assignment: Sentiment Analysis & Trading Performance

## 📋 Project Overview

This comprehensive data science project analyzes the relationship between **market sentiment** (Bitcoin Fear & Greed Index) and **trader performance**. By integrating historical trading data with sentiment indicators, we uncover patterns in profitability, risk, and trader behavior across different market sentiment regimes.

### Key Objectives:
- Analyze how sentiment cycles correlate with trading profits and losses
- Identify actionable insights for trading strategy optimization
- Visualize patterns in trader behavior across different market conditions
- Support data-driven decision-making for risk management

---

## 📁 Directory Structure

```
ds_vishwajeetdaspute/
├── README.md                    
├── notebook_1.ipynb            
├── ds_report.pdf                
│
├── csv_files/                   
│   ├── historical_data.csv      
│   ├── fear_greed_index.csv    
│   └── merged_data.csv          
│
├── outputs/                    
│   ├── sentiment_bar.png        
│   ├── pnl_boxplot.png          
│   ├── correlation_heatmap.png  
│   └── [additional visualizations]
│
└── requirements.txt             
```

---

## 🔍 Analysis Summary

### Data Sources
1. **Historical Trading Data**: Trader performance metrics including entry, exit, profit/loss
2. **Fear & Greed Index**: Daily sentiment scores (0-100) representing market psychology
3. **Merged Dataset**: Combined and cleaned data ready for analysis

### Methodology
- **Data Cleaning**: Handling missing values, outliers, and data type conversions
- **Exploratory Data Analysis (EDA)**: Statistical summaries and distribution analysis
- **Sentiment Segmentation**: Categorizing sentiment regimes (Extreme Fear → Extreme Greed)
- **Correlation Analysis**: Identifying relationships between sentiment and trading outcomes
- **Visualization**: Creating comprehensive charts for pattern discovery

---

## 📊 Key Findings

> Note: Detailed findings and statistical tests are documented in the Jupyter notebook and report PDF.

- Trader performance varies significantly across sentiment regimes
- Specific sentiment thresholds correlate with increased profitability
- Risk metrics (PnL variance) show distinct patterns by market condition
- Actionable insights for timing and position management

---

## 🚀 Quick Start Guide

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Required packages: pandas, numpy, matplotlib, seaborn, scipy

### How to Run

1. **View the Analysis**:
   - Open `notebook_1.ipynb` in Jupyter Notebook
   - Execute cells sequentially to reproduce analysis
   - View inline visualizations and commentary

2. **Review Findings**:
   - Open `ds_report.pdf` for executive summary
   - Contains key insights and recommendations

3. **Explore Data**:
   - Raw datasets available in `csv_files/` folder
   - Use pandas/Excel to inspect specific variables
   - Understand data structure before analysis

4. **View Visualizations**:
   - All charts and figures saved in `outputs/` folder
   - High-resolution PNGs suitable for presentations
   - Regenerated from notebook upon re-execution


---

## 📝 File Descriptions

### `notebook_1.ipynb`
- **Purpose**: Complete analysis pipeline and code
- **Contents**: Data loading, cleaning, EDA, visualizations, statistical tests
- **Runtime**: ~5-10 minutes (depending on system)
- **Output**: All generated figures and statistical summaries

### `ds_report.pdf`
- **Purpose**: Executive summary for stakeholders
- **Contents**: Key findings, recommendations, conclusions
- **Format**: Professional report with charts and explanations
- **Audience**: Non-technical stakeholders, decision-makers

### `csv_files/` Datasets
- **historical_data.csv**: Trading records with timestamps and P&L values
- **fear_greed_index.csv**: Daily sentiment scores from Bitcoin Fear & Greed Index
- **merged_data.csv**: Combined dataset with all variables (output of processing)

---

## 👨‍💼 Author & Contact

**Name**: Vishwajeet Daspute  
**GitHub**: [@vishwaD06](https://github.com/vishwaD06)  
**Project**: Data Science Internship Assignment  
**Date**: November 2025  

### Questions or Feedback?
Feel free to open an issue or contact via GitHub.

---

## 📚 References & Resources

- [Pandas Documentation](https://pandas.pydata.org/docs/) - Data manipulation
- [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html) - Visualization
- [Jupyter Notebook Guide](https://jupyter.org/) - Computing environment
