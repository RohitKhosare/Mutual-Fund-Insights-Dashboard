# 📊 Mutual Fund Analysis & Dashboard

This project analyzes Mutual Funds based on various financial metrics and visualizes insights using Power BI. 
The goal is to help users evaluate risk, return, and ranking of mutual funds for better investment decisions.

---

## 📂 Project Files

| File Name | Description |
|----------|-------------|
| `Mutual_Fund.csv.csv` | Dataset containing mutual fund metrics |
| `Mutual_Fund.ipynb` | Python notebook for data cleaning, scoring & ranking |
| `Dashboard.pbix` | Power BI Dashboard |
| `Mutual_Fund_Dashboard.png` | Screenshot of the final dashboard |

---

## 📁 Folder Overview
Mutual-Fund-Analysis/
│
├── Mutual_Fund.csv.csv
├── Mutual_Fund.ipynb
├── Dashboard.pbix
└── Mutual_Fund_Dashboard.png

---

## 🧠 Tech Stack Used

### 🐍 Python
- Pandas
- Scikit-Learn (Min-Max Normalization)
- NumPy
- Excel Export (openpyxl)

### 📊 Power BI
- Filters
- Ranking Visualization
- KPI Cards
- Bar/Line Charts

---

## 📊 Dataset Description
Dataset includes financial indicators like:

| Metric | Meaning |
|--------|--------|
| returns_1yr | 1-Year Annual Return |
| returns_3yr | 3-Year Annual Return |
| returns_5yr | 5-Year Annual Return |
| sharpe | Risk adjusted return measure |
| sortino | Downside risk measure |
| alpha | Value added over benchmark |
| beta | Risk exposure |
| expense_ratio | Fund management fee |

---

## 🔍 Project Workflow
1️⃣ Data loading  
2️⃣ Handling missing values  
3️⃣ Conversion to numeric  
4️⃣ Normalization (MinMaxScaler)  
5️⃣ Scoring & Ranking  
6️⃣ Exporting Top 30 Funds to Excel  
7️⃣ Visualization using Power BI  

---

## 🚀 Key Outputs

✔ Cleaned & normalized dataset  
✔ Top 30 mutual funds exported as Excel  
✔ Interactive dashboard based on risk & return metrics  

---

## 📊 Dashboard Preview
(Attached Screenshot)

![Dashboard Preview](<img width="1435" height="810" alt="Mutual_Fund_Dashboard" src="https://github.com/user-attachments/assets/8f450f2b-b40d-4926-b39a-803be6eca2e9" />
)

---

## 🏁 Conclusion
The analysis successfully ranks the mutual funds considering growth and risk indicators.  
The dashboard helps investors quickly identify the best mutual funds to invest in.

---

## ✍️ Author
**Rohit Khosare**  
(Data Analyst | Python | Power BI)

---

## 📜 License
Free to use for learning and portfolio purposes.
