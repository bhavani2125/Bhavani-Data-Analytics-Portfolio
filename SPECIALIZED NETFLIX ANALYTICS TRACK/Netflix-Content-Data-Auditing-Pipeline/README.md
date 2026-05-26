A Python-based data auditing and visualization pipeline that processes the raw Netflix titles dataset — performing automated cleaning, structural profiling, metadata extraction, and custom visualization generation using precise brand color schemes.

Project Overview
Domain	Data Engineering / Content Analytics
Tools Used	Python (Pandas, NumPy, Matplotlib, Seaborn), Google Colab, Claude AI (claude.ai)
Dataset	Netflix_Titles.csv
Key Files	analysis.py, cleaned_netflix_titles.csv, data_info.txt, output/
Deliverable	Cleaned dataset + data profile log + visualization outputs

What I Did
•	Developed sanitization workflows using Pandas and NumPy to profile structural parameters (rows, columns, dtypes), detect and handle missing values, and export a clean cleaned_netflix_titles.csv.: Automated Data Cleaning
•	Automated generation of data_info.txt — capturing index schema, column names, data types, and null counts across all features including cast, directors, release year, rating, and country.: Structural Metadata Profiling
•	Engineered standalone visual models using Matplotlib and Seaborn with exact Netflix brand hex codes (#B20710, #E50914, #FF4C4C) — clean charts without borders or gridlines.: Custom Color-Coded Visualizations
•	Used Claude AI (claude.ai) to help write Python code, debug errors, and refine the analysis approach. Project managed via CLAUDE.md in the Claude Projects environment.: AI-Assisted Development

How to Run
# 1. Open in Google Colab or Jupyter Notebook
# 2. Upload Netflix_Titles.csv to your environment
# 3. Run analysis.py
python analysis.py
# 4. Outputs saved to output/ folder

Files in This Project
   analysis.py  —  Main Python auditing and visualization script
   Netflix_Titles.csv  —  Raw input dataset
   cleaned_netflix_titles.csv  —  Cleaned output dataset
   data_info.txt  —  Automated structural metadata log
   Netflix_Readme.txt.docx  —  Project documentation
   CLAUDE.md  —  Claude AI project configuration
