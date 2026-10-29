# E-commerce Sales & Customer Behaviour Analysis

## Project Overview
This project uses Python to analyse historical e-commerce transaction data and identify patterns in sales performance, product demand, country-level sales, and customer purchasing behaviour.

## Business Objectives
- Measure overall sales performance using key performance indicators (KPIs).
- Analyse monthly revenue, units sold, and average order value.
- Identify top-performing products and countries.
- Understand one-time and repeat customer purchasing behaviour.
- Develop business recommendations from the analysis.

## Tools & Technologies
- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn

## Project Workflow
1. Loaded and explored the transaction dataset.
2. Identified missing values, duplicate records, cancellations, returns, and unusual prices.
3. Cleaned the data and documented analytical decisions.
4. Calculated sales KPIs and grouped sales by month, product, and country.
5. Analysed customer purchasing behaviour.
6. Created visualisations and summarised business findings.

## Key Results
- **Total revenue:** £10,631,048.74
- **Units sold:** 5,572,419
- **Unique invoices:** 19,959
- **Customers with identified IDs:** 4,338
- **Average order value:** £532.64
- **Repeat-customer revenue share:** 93.1% of revenue associated with identified customers

## Business Recommendations
- Encourage repeat purchases through customer-retention initiatives.
- Monitor monthly sales trends to support seasonal planning.
- Evaluate top-performing products and countries when planning inventory and marketing.
- Improve customer identification to strengthen customer-level reporting.

## Limitations
- The dataset covers December 2010 to December 2011.
- December 2011 contains data only through December 9.
- Missing customer IDs limit customer-level analysis.
- Cost data is unavailable, so profit and profit margins cannot be calculated.
- The analysis is descriptive and does not establish the causes of sales patterns.

## Repository Contents
- `Ecommerce_Sales_Customer_Analysis.ipynb` — Jupyter Notebook containing the data cleaning, analysis, calculations, and visualisations.

## Conclusion
This project demonstrates the use of Python for data cleaning, exploratory data analysis, KPI calculation, visualisation, and customer behaviour analysis. It highlights the value of repeat customers while documenting the limitations that should be considered when interpreting the results.
