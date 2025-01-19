# Dynamic Cash Flow Statement Visualisation

## Overview

This project demonstrates a customised Cash Flow Statement visualisation developed in Power BI. Designed for financial analysts and investment professionals, this solution emphasises clarity, interactivity, and actionable insights, making it ideal for financial reporting and scenario analysis.

## Key Features

### 📊 Dynamic and Interactive Table

- Presents a clean and professional cash flow statement, dynamically calculated and formatted for easy comprehension while maintaining hierarachy of activities.
- Supports drill-down functionality to analyse cash flow activities at different levels of detail.

### 🎨 Custom Conditional Formatting

- Color-coded visual indicators highlight year-over-year changes (e.g., green for positive changes, red for negative).
- Conditional formatting applied to both values and percentage changes to quickly spot trends and outliers.

### 📈 Integrated Delta Bars

- **(*My favourite feature*)** Visual "Delta Bar" indicators display absolute and percentage changes in key cash flow metrics .
- Delta Bars dynamically adjust to highlight both positive and negative variances.

### 🛠️ Custom Calculation Groups

- Streamlines repetitive rows by using a calculation group to condense multiple redundant values.
- Implements a hierarchical structure to display starting balances, net changes, and ending balances intuitively.

### 🎯 Enhanced Readability

- Includes blank rows and subtle borders for cleaner separation between sections like operating, investing, and financing activities.
- Allows for alignment adjustments and row padding to maintain a professional layout.

### 🚀 Scalable for Any Dataset

- Designed to work with diverse datasets by enabling easy configuration of table names and granularity levels.
- Fully customisable for different levels of financial reporting, from high-level summaries to granular cash flow details.

## Use Cases

### 💼 For Finance Professionals

- Quickly generate insightful cash flow reports with year-over-year comparisons for internal and external stakeholders.
- Gain better visibility into operating, investing, and financing activities with dynamic breakdowns.

### 📉 For Investment Analysts

- Track trends and variances in cash flow metrics to evaluate financial performance over time.
- Identify key drivers of change in cash flow for valuation models and investment decision-making.

### 🧩 For Business Insights

- Integrate with existing Power BI dashboards to combine cash flow data with profitability, balance sheet, or market performance metrics.

## Screenshots

A sample visualisation of the Cash Flow Statement with dynamic formatting and Delta Bars.
![Sample Statement](https://github.com/DashOfRisk/PowerBI-Dashboard-Project/blob/a7101f5f7760c09a47e97e6473200339abcf7331/Financial%20Statement%20Analysis%20V1/Cash%20Flow%20Statement%20V1.png)

## How It Works

### Data Transformation

- Raw cash flow data is structured into operating, investing, and financing activities.
- Additional hierarchies are created for start-of-year and end-of-year totals.

### Formatting Features

- Conditional formatting applied to values, percentages, and Delta Bars for clear visualisation.
- Subtotals and grand totals dynamically calculated and formatted.

### Customisation Options

- Adjustable row padding, column alignment, and font sizes for maximum flexibility.
- Blank rows and borders for improved readability moving away from yet another generic statement.

### Calculation Groups

- Custom logic eliminates redundant rows while maintaining a clear hierarchy.
- Provides flexibility to adapt for different datasets and requirements.

## Skills Demonstrated

- **Power BI Development:** Advanced table visualisations, hierarchical structures, and conditional formatting.
- **Data Modeling:** Efficient organisation of cash flow data using calculation groups and measures.
- **Financial Acumen:** Tailoring the visualisation to meet the needs of financial reporting and investment analysis.
- **Problem-Solving:** Addressing challenges like repetitive data and visual clutter with innovative solutions.


## Technologies Used

- Power BI including Power Query
- DAX (Data Analysis Expressions)
- Dynamic Conditional Formatting

## Why This Project Stands Out

This project bridges the gap between finance and technology, demonstrating how advanced Power BI features can elevate financial reporting. It highlights attention to detail, data visualisation skills, and financial knowledge—qualities essential for finance and investment roles.

## Future Enhancements

- Use Python to import data and enhance reporting skills for a wide range of companies, making the visual versatile.
- Add forecasting capabilities to project future cash flow trends.
- Develop export options for integration with Excel or other financial systems.

## 📜 Disclaimer
This project was inspired by Andrzej Leszkiewicz as well as Injae Park in the Power BI Park community. While the original concept, structure, and guidance of this project were provided by Injae Park, I have prior permission to showcase this project as my own. The PBIX file or any associated materials from this Proof of Concept (PoC) report will only be provided with prior permission from me. Any unauthorised distribution, replication, or commercial use of the materials in this project is strictly prohibited.
