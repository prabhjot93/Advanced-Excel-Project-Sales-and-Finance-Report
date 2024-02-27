# Advanced-Excel-Project-Sales-and-Finance-Report

Analysed Hardware company's global sales. This report specifically compares different countries Target sales Vs actual performance for year 2021 using Advanced Excel(Power Pivot, DAX, Pivot tables). Used Data Model and built relationships among sales and target table to calculate percentage difference. Designed [Market Performance Report](https://github.com/prabhjot93/Advanced-Excel-Project-Sales-and-Finance-Report/blob/main/Market%20Performance.pdf) and ([Profit & Loss Report](https://github.com/prabhjot93/Advanced-Excel-Project-Sales-and-Finance-Report/blob/main/Profit%26Lost%20report.pdf))


This project also covers Net Sales Performance Report helps business management to monitor and evaluate their sales activities and customers performance in each Fiscal Year. Use of Power Pivot empowered me to create resilient data model, establish table relationships, and to derive profound insights through advanced calculations. Through this project, I explored crucial concepts to ensure precise data analysis and interpretation.

Used DAX measures for Power Pivot
COGS=SUM(factsalesmonthly[total cogs])

Gross margin=[net sales]-[COGS]

GM%= DIVIDE([Gross Margin],[net sales],0)

sales 2020 vs 2021=divide([net_sales_2021],[net sales 2020],0)

Target-2021=[net_sales_2022]-[Target2021]

2020 Vs 2019 sales= DIVIDE([net_sales_2020],[net sales 2019],0)

