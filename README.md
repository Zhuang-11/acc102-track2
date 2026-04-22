# ACC102 Track 2: Comparative Stock Performance Analysis

## 1. Problem & User
This project analyzes the cumulative stock performance of Apple (AAPL) and Microsoft (MSFT) from 2022 to 2024. It aims to compare their performance trends and provide clear data evidence for basic financial analysis learning.

## 2. Data
- **Source**: WRDS CRSP Monthly Stock Database
- **Access Date**: 22 April 2025
- **Time Period**: 2022-01-01 to 2024-12-31
- **Companies**:
  - Apple (AAPL): permno 14593
  - Microsoft (MSFT): permno 10107
- **Variables**: date, permno, monthly return (ret), price (prc)

## 3. Methods
1. Data Extraction: Extract monthly stock data from WRDS using SQL query
2. Data Cleaning: Remove missing values and show before/after comparison
3. Data Processing: Split dataset by company
4. Analysis: Calculate cumulative returns for performance comparison
5. Visualization: Plot clear cumulative return comparison line chart
6. Conclusion: Summarize key findings from the chart and analysis

## 4. Key Findings
- Microsoft achieved higher cumulative returns than Apple during 2022-2024.
- Both companies showed positive overall performance in the three-year period.
- Apple had higher volatility, while Microsoft showed more stable growth.

## 5. How to run
1. Make sure you have Python installed and access to the WRDS database.
2. Install required packages using the command:
   `pip install pandas matplotlib wrds`
3. Open and run the `notebook.ipynb` file in Jupyter Notebook.
4. Verify the outputs including raw data tables, cleaning results, cumulative return chart, and key findings.

## 6. Limitations & next steps
### Limitations
- The analysis is limited to two large technology companies; conclusions cannot represent other industries.
- Only monthly data is used, so short-term price volatility and daily market events are not captured.
- Return calculations do not include dividends, transaction costs, or inflation adjustments.
- Macroeconomic factors such as interest rate changes are not included in the analysis.

### Next steps
- Include more companies from different industries for a more comprehensive comparison.
- Extend the time period to analyze longer-term performance trends.
- Add dividend reinvestment and transaction cost simulation for more accurate return results.
- Incorporate macroeconomic indicators to support deeper analysis.

## AI Disclosure
- Tool: ChatGPT，Doubao
- Model: GPT-4o
- Use: Code debugging, writing support, and project organization