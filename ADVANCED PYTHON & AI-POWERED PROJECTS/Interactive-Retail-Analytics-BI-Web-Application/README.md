A fully deployed interactive business intelligence web application built with Python and Streamlit — enabling dynamic EDA on the Sample Superstore retail dataset through real-time filters, interactive charts, and statistical correlation models.

Project Overview
Domain	Retail Analytics / Business Intelligence Web App
Tools Used	Python (Pandas, Plotly Express, Streamlit)
Dataset	Sample - Superstore.xls
Key Files	Dashboard.py
Deliverable	Live interactive web dashboard (Streamlit app)

What I Did
•	Engineered a responsive wide-layout Streamlit web application that loads the Superstore dataset and delivers dynamic EDA with a professional UI.: Full-Stack Dashboard
•	Programmed multi-layered conditional sidebar filters allowing users to slice data by Date Range, Region, State, and City — all charts update in real time.: Sidebar Filter Matrix
•	Integrated Plotly Express donut-hole charts visualizing sales distribution by region.: Regional Pie Charts
•	Built an interactive treemap (Region → Category → Sub-Category) to explore hierarchical revenue contribution at every level.: Sales Treemap
•	Generated a multi-variable scatter plot charting Sales vs. Profit, with marker size scaled by Quantity to reveal high-volume transaction clusters.: Scatter Correlation Chart
•	Displayed headline metrics including Total Sales, Total Profit, and Profit Margin in styled summary cards at the top of the dashboard.: KPI Summary Cards

How to Run
# Install dependencies
pip install streamlit pandas plotly openpyxl
# Run the app
streamlit run Dashboard.py
# Open in browser: http://localhost:8501

Files in This Project
   Dashboard.py  —  Main Streamlit application script
   Sample - Superstore.xls  —  Retail dataset used for analysis
