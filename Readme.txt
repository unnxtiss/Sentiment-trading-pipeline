============================================================
       AI-POWERED SENTIMENT & PRICE PREDICTION PIPELINE
============================================================

Author: Unnati


------------------------------------------------------------
1. PROJECT OVERVIEW
------------------------------------------------------------
This project builds an automated Python pipeline that ingests 
alternative financial data (news sentiment via Exa.ai), analyzes 
market indicators, generates a structured institutional brief, and 
trains a machine learning regression model using out-of-sample 
validation to predict an asset's next-day price (n+1).

------------------------------------------------------------
2. REPOSITORY FILE STRUCTURE
------------------------------------------------------------
- Ingestion.ipynb : The primary Jupyter Notebook containing all 
                    executable code blocks for data ingestion, 
                    sentiment processing, metric calculation, 
                    report generation, and ML model training.
- scraped_news.csv : Raw news articles and text snippets fetched via 
                     the Exa.ai API for monitored assets (AAPL, 
                     TSLA, MSFT, NVDA, GOOGL).
- asset_metrics.csv : Processed dataset containing current prices, 
                      support/resistance levels, sentiment scores, 
                      and social mention summaries.
- report.md : Visual institutional report sorted and formatted in 
              Markdown for professional stakeholder review.
- Readme.txt : Project documentation and execution guidelines.

------------------------------------------------------------
3. HOW TO RUN THE PIPELINE
------------------------------------------------------------
1. Open Jupyter Notebook in your working environment.
2. Launch 'Ingestion.ipynb'.
3. Ensure required Python libraries are installed:
   !pip install pandas numpy yfinance textblob scikit-learn exa-py
4. Run all cells sequentially from top to bottom to reproduce 
   the data collection, sentiment modeling, and price predictions. sequentially.