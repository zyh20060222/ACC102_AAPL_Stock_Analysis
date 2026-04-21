Track 2: GitHub Data Analysis Project 
1. Problem & User
This project analyzes AAPL monthly stock performance to demonstrate a complete Python data workflow. The intended audience is the course instructor and peers reviewing the data product.
2. Data Source
   • Source: WRDS CRSP Monthly Stock File
   • Access date: April 2026
   • Period: 2020–01 to 2025–12
   • Key variables: date, price (prc), return (ret), cumulative return
3. Python Methods
   1. Connect to WRDS and run SQL query
   2. Data cleaning and date formatting
   3. Calculate monthly and cumulative returns
   4. Visualize price trend with matplotlib
   5. Export results to Excel
4. Key Findings
   • AAPL stock price declined in early 2020 and recovered strongly afterward
   • Steady long-term upward trend from 2021 to 2025
   • Positive cumulative returns over the five-year period
   • Volatility corresponded to macroeconomic conditions
5. How to Run
   1. Open the Jupyter notebook
   2. Run all cells sequentially
   3. Ensure required packages: pandas, wrds, matplotlib
6. Product Links
   • GitHub Repository: https://github.com/zyh20060222/ACC102_AAPL_Stock_Analysis
   • Demo Video: https://video.xjtlu.edu.cn/Mediasite/Play/10acb7ac58a046f09a0334523d1eda1f1d
   • Only monthly data is used; higher-frequency data could provide more details
   • No advanced modeling or risk metrics included • Future versions can add moving averages and volatility analysis
