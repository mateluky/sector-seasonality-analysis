# 📈 Sector Seasonality Analysis in Financial Markets

*(Data Science Portfolio Project – Finance Analytics)*

This project analyzes **historical sector performance across months and seasons** using Python.  
The goal is to identify whether certain market sectors show **recurring seasonal patterns** that could inform **investment strategies, portfolio allocation, and risk management**.


## 📊 Data Source
- Data obtained from [Yahoo Finance](https://finance.yahoo.com/) by scraping historical sector ETF performance.  
- Data collection was handled as part of a group project.  
- This repository focuses on **my contribution**:  
  - **Exploratory seasonality analysis**  
  - **Visualization of trends**  
  - **Interpretation of results**  
- Cleaned CSV files are included in the `Data/` folder for reproducibility.

## 📁 Project Structure
```bash
.
├── PROJECT_sector_seasonality_analysis.ipynb # Main notebook with full analysis
├── Data/ # Cleaned input data (CSV format)
├── requirements.txt # Dependencies for reproducibility
└── README.md # Project description and usage guide
```

## 🎯 Objectives
- Examine **monthly and seasonal sector performance**.  
- Detect recurring **calendar effects** across sectors.  
- Compare cyclical vs defensive sectors.  
- Communicate insights with clear **visualizations and metrics**.


## 🧪 Methodology
1. **Data Preprocessing**
   - Import cleaned sector returns from Yahoo Finance.
   - Aggregate by month and season.
   - Normalize returns for comparability.

2. **Seasonality Analysis**
   - Compute average monthly returns per sector.
   - Detect recurring overperformance/underperformance patterns.
   - Compare across multiple years.

3. **Visualization**
   - Heatmaps of monthly sector returns.
   - Bar and line charts comparing sectors.
   - Highlight top/bottom months for each sector.


## 📈 Key Results
- Certain sectors exhibit **consistent seasonal outperformance** (e.g., technology in Q4).  
- Defensive sectors (e.g., utilities, consumer staples) show **lower seasonal variation**.  
- Cyclical sectors (e.g., energy, industrials) demonstrate **stronger calendar effects**.  
- Seasonality insights may support **timing and allocation strategies**.  

*(Detailed plots and charts are available in the notebook.)*


## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/sector-seasonality-analysis.git
   cd sector-seasonality-analysis
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Launch the notebook:
   ```bash
   jupyter notebook PROJECT_sector_seasonality_analysis.ipynb

## 📦 Requirements

- Python 3.11+  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- jupyter  

Full dependencies are listed in [requirements.txt](requirements.txt).

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

