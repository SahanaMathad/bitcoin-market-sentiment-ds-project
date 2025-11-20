# ds_Sahana_Mathad — Bitcoin Sentiment & Trader Behaviour Analysis

**Project:** Relationship between trader behaviour (profitability, risk, volume, leverage) and Bitcoin market sentiment (Fear vs Greed).  
**Team / Role:** Solo project — Data exploration, feature engineering, analysis, and reporting.  
**Environment:** Google Colab (link below), Python (pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels), GitHub.

---

**Project Highlights**
- Investigated how trader decisions (leverage, position size, PnL) align with Fear/Greed market regimes.
- Performed robust EDA, time-aligned datasets, and created visual signals useful for trading strategy hypotheses.
- Produced actionable insights (e.g., signal ideas, risk management recommendations) backed by charts and statistical tests.

---

**This repository contains two versions of the analysis notebook: one developed using Jupyter Notebook and another adapted specifically for execution in Google Colab.**

**📁 Repository structure**

ds_Sahana_Mathad/

├── notebook1_JupyterNotebook.ipynb 

├── notebook2_GoogleCollab.ipynb 

├── csv_files/

│ └── fear_greed_index.csv

  └── historical_data.csv

├── outputs/

│ ├── closed_pnl_distribution.png

│ ├── closed_pnl_outliers.png

  ├── daily_closed_pnl.png
 
  ├── feature_importances.png

  ├── market_sentiment_over_time.png

  ├── pnl_by_sentiment.png

  ├── trader_features_correlation.png

│ └── confusion_matrix.png

├── ds_report.pdf # Final PDF report

└── README.md


---

**🔗 Dataset sources**
- Historical Trader Data (Hyperliquid) — provided in assignment instructions. :contentReference[oaicite:1]{index=1}  
- Bitcoin Fear & Greed Index — provided in assignment instructions. :contentReference[oaicite:2]{index=2}

** ▶ How to run the analysis (Google Colab)**
1. Open `notebook_1.ipynb` in Google Colab.
2. Upload datasets or mount your Google Drive and move the CSVs to `/content/drive/MyDrive/ds_<YourName>/csv_files/`.
3. Run all cells (Runtime → Run all).
4. Export notebook to PDF: File → Print → Save as PDF (or `File → Download → Download .ipynb` and use `nbconvert`).

---

** 📌 What to look for inside the notebook**
- **Data ingestion & cleaning**: time parsing, timezone alignment, removing duplicates, handling missing closedPnL/leverage values.
- **EDA**: distribution plots, time series of sentiment vs aggregate trader PnL, leverage histograms split by sentiment regime.
- **Signal extraction**: rolling win-rate, avg leverage in Fear vs Greed, large-trade behaviours.
- **Statistical validation**: t-tests / Mann-Whitney tests for differences, correlation analysis, lagged cross-correlations.
- **Takeaways & suggestions**: actionable trading risk controls and signal ideas.

---

** 📎 Deliverables**
- Cleaned CSV(s) inside `/csv_files/`.
- Visual outputs inside `/outputs/`.
- `ds_report.pdf` — polished written report summarizing methodology, results, and recommendations.
- Link to the Colab notebook with runnable code.
**- You can access the analysis notebooks through the following links:**
1. https://colab.research.google.com/drive/1ihYgO8Qv-IhIBv0m-0WoAmy7W1rlHVnF
2. https://colab.research.google.com/drive/1W8_kRfoPIewzyuk4vIUuwc1YJwY0N1Iy#scrollTo=8ndW0ZYkVUdl

---

** 🧾 Contact & Next steps**
If you want, I can:
- Replace the placeholder metrics and screenshots in the report with actual outputs from your notebook (please paste the notebook link),
- Optimize wording for a specific job description.

---

**Licence**
MIT — feel free to reuse and adapt.
