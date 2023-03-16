# Performance Report

## Overview

This project aims to develop a business intelligence solution for a hospitality group, allowing them to gain insights into their performance and make data-driven decisions. The solution will be built using Microsoft Power BI, using data extracted from the company's existing ERP system and hotel management software.

## Objectives
- Develop a business intelligence reporting solution that allows the company to monitor their financial performance and make data-driven decisions.
- Enable the company to identify areas of their business that require improvement and leverage trends and patterns in their data for more accurate decisions and planning.
- Provide insights into key business indicators.

## Requirements
The dashboard should present financial and operational information related to the company. In the financial aspect, the following topics are to be presented:

- `Balance Sheet`
- `Income Statement`
- `Turnover`
- `Annual Revenue Growth`
- `Monthly Revenue Growth`
- `EBITDA`
- `EBITDA Margin`
- `EBIT`
- `EBIT Margin`
- `EBT`
- `Net Income`
- `Economic and financial ratios`

The economic and financial ratios developed are related to financial structure, indebtedness, liquidity, activity indicators, profitability, and performance. To analyze the company's financial structure, the ratios of financial autonomy, financial dependence, coverage of non-current assets, and overall solvency were calculated. Regarding indebtedness, the following indicators were calculated: indebtedness, debt structure, cost of obtained financing, effect of interest incurred, medium and long-term debt capacity, and weight of non-interest-bearing liabilities. Regarding liquidity, the percentages of general, reduced, and immediate liquidity were determined, and the values of working capital, working capital requirements, and net treasury were calculated. Activity indicators correspond to the determination of `PMP`, `PMR`, and `PMRI`, and the calculation of asset turnover, inventory turnover, and treasury cycle. Regarding profitability, the profitability of services provided, profitability of assets and permanent capital, gross value added, economic profitability, wage productivity, and expenditure and average productivity per employee were calculated. To enable evaluation and analysis of hospitality performance, the following indicators were defined: `OCC`, `GOPPAR`, `TRevPAR`, `TRevPEC`, and `TRevPOR`.

The operational indicators developed and presented on the dashboard are:

- `Revenue by service type`
- `Average occupancy rate`
- `Weight of personnel expenses in the different sections of total personnel expenses`
- `Personnel expenses/total expenses`
- `Personnel expenses/turnover`
- `Weight of CMVMC and personnel expenses inherent to F&B in restaurant revenue`
- `Weight of F&B expenses in restaurant revenue`
- `Total F&B loss`

In addition, a Top 10 Sales and a Top 10 Customers, both by nationality, were created.

## Definition
The project will involve the creation of a data model by extracting and importing data from the company's ERP system (trial balance) and hotel management software (occupation data) into Microsoft Power BI. The data will be modeled, including the creation of the following matrices:

- `Balanço Patrimonial` (Balance Sheet) 
- `Demonstração de Resultados` (Income Statement) 
- `Rendimentos` (Revenue) 
- `Gastos com pessoal` (Personnel expenses) 

The matrices will define the corresponding accounts for each item in the structure.

Measures will be created, including the more complex `balanço` and `demonstração_resultados`, that will allow these financial statements to be presented in interactive visualizations.

An interactive report will then be developed using advanced data analytics and visualization techniques.

## Conclusion
This BI report provides a comprehensive overview of the company's financial and operational performance. By presenting key financial ratios and indicators, the company can evaluate its financial structure, indebtedness, liquidity, activity, profitability, and performance. This information allows decision-makers to identify areas of weakness and develop strategies to improve the company's financial and operational performance.

Moreover, the operational indicators developed provide the company with a clear picture of revenue by service type, average occupancy rate, personnel expenses, and catering expenses. These indicators allow the company to make informed decisions regarding staffing levels, service offerings, and pricing.

Overall, the development of this dashboard allows the company to monitor and evaluate its performance effectively, providing a significant competitive advantage. With access to actionable data and key indicators, the company can quickly respond to changes in the market and make data-driven decisions that contribute to long-term success.
