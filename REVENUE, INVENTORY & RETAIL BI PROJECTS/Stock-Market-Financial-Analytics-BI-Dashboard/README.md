An end-to-end financial analytics pipeline that ingests and cleans raw stock market data using Python, then delivers interactive market intelligence dashboards in Tableau — covering 6 major tech equities and over 1 trillion in total trading volume.

Project Overview
Domain	Financial Analytics / Stock Market Intelligence
Tools Used	Python (Pandas, Matplotlib, Seaborn), Tableau, Google Colab
Dataset	Raw_Stock_files — historical OHLCV data for 6 tech stocks
Key Files	Python_File/, Cleaned_Stock_files/, Stock_Market_Tableau_Dashboard/
Deliverable	Cleaned datasets + Python analysis scripts + Tableau Dashboard

Business Problem
•	Raw stock data files were inconsistent, unstructured, and spread across multiple files. The goal was to build a reliable pipeline to clean this data and then create a visual dashboard that lets analysts track trends and compare equities.

What I Did
•	Engineered a Python pipeline using Pandas in Google Colab to ingest raw OHLCV data from Raw_Stock_files, handle inconsistencies, standardize formats, and export clean datasets to Cleaned_Stock_files.: Automated ETL Pipeline
•	Apple (AAPL), Google (GOOGL), Facebook (META), Tesla (TSLA), Nvidia (NVDA), Twitter (TWTR) — capturing 1.07 Trillion in Total Trading Volume.: Stocks Covered
•	Constructed trend line charts comparing Opening Prices against 50-day (MA50) and 200-day (MA200) Simple Moving Averages to isolate technical buy/sell signals.: Moving Average Analysis
•	Generated a custom histogram mapping Percent Change in Price across volatile market windows, with color groupings per asset to isolate daily frequency spreads.: Distribution Histogram
•	Built a comprehensive interactive dashboard for multi-stock performance comparison, trend visualization, and volume analysis.: Tableau Dashboard

Key Insights
•	Nvidia and Tesla showed the highest price volatility across the analysis window.
•	The MA50/MA200 crossover analysis revealed key trend inflection points for long-term investors.
•	Volume spikes correlated strongly with major earnings announcement windows.

Files in This Project
 Raw_Stock_files/  —  Original unprocessed stock data
 Cleaned_Stock_files/  —  Cleaned and standardized output datasets
 Python_File/  —  Python scripts for ETL and analysis
 Stock_Market_Tableau_Dashboard/  —  Interactive Tableau dashboard files
