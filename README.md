📊 Taxpayer Analytics & Tax Regime Comparison Dashboard
📌 Project Overview

This project presents an interactive Power BI dashboard designed to analyze taxpayer data and compare tax outcomes under the Old and New Tax Regimes. The dashboard focuses on income distribution, tax payable, filing compliance, and demographic insights to support data-driven decision-making.Dataset consists of anonymized taxpayer records with income, tax regime, profession, city, and demographic attributes.

🛠 Tools & Technologies

Power BI

DAX (Data Analysis Expressions)

Microsoft Excel
📘 Data Dictionary
Column Name	   Data              Type	Description	                        Example Values
Taxpayer_ID	  Integer  	   Unique identifier for each taxpayer	            101, 102
Annual_Income	Numeric	     Total annual income of the taxpayer	             850000
Tax_Regime	  Text	       Tax regime selected by taxpayer	                Old, New
Tax_Payable 	Numeric	      Final tax payable after calculations	           92500
Tax_Savings	  Numeric	     Difference between old and new regime tax	        18600
Income_Slab	  Text	       Income category based on annual income	           2.5L–5L
Profession	  Text	          Occupation of the taxpayer	                   Manager
Gender	      Text	             Gender of the taxpayer	                    Male, Female
City	        Text	               City of residence	                       Kolkata
Filed_Return	Boolean	      Whether tax return was filed	                  TRUE / FALSE
📈 Key Features

KPI cards showing Total Tax Payable, Average Annual Income, Total Taxpayers, and Filing Compliance %

Comparison of Old vs New Tax Regime using clustered column and bar charts

Gender-wise analysis using donut chart

Interactive slicers for Tax Regime and Gender

Dynamic filtering across all visuals

Clean formatting following professional consulting dashboards

Tooltip usage for enhanced insights without clutter

📊 DAX Measures Implemented

Total Tax Payable

Average Annual Income

Total Taxpayers

Filed Returns Count

Percentage of Taxpayers Benefiting

🎯 Business Insights

Identifies which tax regime benefits more taxpayers

Highlights filing compliance patterns

Enables quick comparison of tax burden across regimes

Supports policy and financial analysis use cases
Applicable to tax analytics, compliance reporting, and policy impact analysis use cases relevant to consulting and financial advisory teams.

📂 Files Included

Power BI Dashboard (.pbix)

Source dataset (.csv)

Project documentation (README.md)

🔗 Use Case

This project demonstrates practical skills in data visualization, DAX modeling, and business analytics, suitable for analytics and technology internship roles.
