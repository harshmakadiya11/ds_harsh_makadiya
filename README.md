# 📊 Data Science Assignment — Trader Behavior vs Market Sentiment

## 👤 Candidate
**Name:** Harsh Makadiya 
**Folder:** `ds_harsh_makadiya`  

---

## 📂 Project Overview
This project analyzes the relationship between **trader behavior** (profitability, risk, trading volume, buy/sell bias, volatility) and **market sentiment** (Fear vs Greed).  

The analysis explores whether traders align with overall sentiment or diverge from it, and identifies **hidden signals** that could influence smarter trading strategies.

---

## 🔗 Google Colab Notebook
You can view and run the full analysis here:  
👉 [Open notebook_1.ipynb in Google Colab](https://colab.research.google.com/drive/1fXYRhC3XfYH240aOd5IAV8husP77tQrJ?usp=sharing)


---

## ⚙️ Setup Instructions
1. Open the notebook in **Google Colab** using the link above.  
2. Mount Google Drive inside Colab:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
3.Update project folder name:

    CANDIDATE_NAME = "<your_name>"
    ROOT_DIR = f"/content/drive/MyDrive/ds_{CANDIDATE_NAME}"
4.Run all cells to reproduce results.
5.Outputs (charts, CSVs) will be saved automatically in Google Drive under:

    /content/drive/MyDrive/ds_<your_name>/

## 📊 Key Deliverables

- **Exploratory Data Analysis (EDA):**
  - Sentiment distribution  
  - Boxplots  
  - Heatmaps  
  - Correlations  

- **Trading Behavior Analysis:**
  - Profitability by sentiment  
  - Win-rate by sentiment  
  - Risk-adjusted returns  
  - Trading volume trends  
  - Extreme Fear vs Extreme Greed comparison  
  - Lagged correlation between sentiment & PnL  

---

## ✅ Summary of Insights

- **Profitability** → Highest in *Extreme Fear*, lowest in *Greed*.  
- **Win-rate** → Highest in *Extreme Greed (88%)*, lowest in *Extreme Fear (64%)*.  
- **Volume** → Strongest in *Fear ($149M)*, weakest in *Extreme Fear ($38M)*.  
- **Risk (Volatility)** → Highest in *Extreme Fear*, lowest in *Greed*.  
- **Risk-Adjusted Returns** → Best in *Neutral*, weakest in *Greed*.  
- **Lagged Correlation** → *Greed predicts weaker future returns, Fear predicts stronger ones.*  

---

## ✅ Conclusion

- **Extreme Fear** → High risk, high reward (*contrarian buy opportunities*).  
- **Extreme Greed** → Safe but low profitability (*reduce exposure*).  
- **Neutral** → Most consistent and efficient environment.  
- **Greed overall** → Weakest efficiency, risk of overtrading.  


