# 📉 Stock Market Crash Analysis

This repository contains a **Stock Market Crash Analysis** project built with Python (Jupyter Notebook). The project analyzes historical stock market data to identify trends, patterns, and anomalies during critical periods.

## 📂 Repository Structure

```
├── StockMarketCrash.ipynb   # Jupyter Notebook with full analysis & code
├── data/                    # Folder for stock market dataset
├── README.md                # Project documentation
```

## 📊 Dataset

The dataset contains historical stock market records with the following columns:

* **Date** → Trading day (dd-mm-yyyy)
* **Open** → Opening price of the index
* **High** → Highest price of the day
* **Low** → Lowest price of the day
* **Close** → Closing price of the day
* **Volume** → Trading volume

Example (first 5 rows):

| Date       | Close   | High    | Low     | Open    | Volume |
| ---------- | ------- | ------- | ------- | ------- | ------ |
| 01-07-1997 | 4300.86 | 4301.77 | 4247.66 | 4263.11 | 0      |
| 02-07-1997 | 4333.90 | 4395.31 | 4295.40 | 4302.96 | 0      |
| 03-07-1997 | 4323.46 | 4393.29 | 4299.97 | 4335.79 | 0      |
| 04-07-1997 | 4323.82 | 4347.59 | 4300.58 | 4332.70 | 0      |
| 07-07-1997 | 4291.45 | 4391.01 | 4289.49 | 4326.81 | 0      |

## 🔍 Project Objectives

* Perform **exploratory data analysis (EDA)** on historical stock data.
* Visualize **price trends** and detect anomalies before/after crash periods.
* Use **statistical & technical indicators** (moving averages, volatility, etc.).
* Build insights into **market behavior during crashes**.

## 🛠️ Tools & Technologies

* **Python** (Pandas, NumPy, Matplotlib, Seaborn)
* **Jupyter Notebook**
* **Data Visualization & Statistical Analysis**

## 📈 Key Analysis & Visualizations

* Trendline of stock prices over time
* High vs. Low price range plots
* Moving average and volatility analysis
* Crash period visualization

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/HarshalNikhade/Stock-Market-Crash.git
   cd StockMarketCrash
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:

   ```bash
   jupyter notebook StockMarketCrash.ipynb
   ```

## 📌 Future Scope

* Add **machine learning models** to predict crash probabilities.
* Extend dataset to include **global indices & volume trends**.
* Integrate with **real-time APIs (Yahoo Finance, Alpha Vantage)**.

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

