# 🔎 Methodology — Mercedes-Benz Business Performance Dashboard

## 1. Objective 🎯

The objective is to present financial performance, profitability trends, research and development expenditure, and geographical vehicle sales in an interactive Power BI report covering 2022–2025.

## 2. Data Preparation 🧹

The project organizes financial, quarterly, geographical, and reference data into tables suitable for Power BI reporting.

The model includes year, quarter, metric, region, and country-related fields or dimensions.

## 3. Key Performance Indicators 📊

The dashboard presents the following KPIs:

- **Total Revenue:** Revenue aggregated under the report's current filters.
- **Net Profit:** Net profit aggregated under the report's current filters.
- **Total Vehicles Sold:** Vehicle sales aggregated under the report's current filters.
- **Revenue YoY Growth:** Percentage change in revenue compared with the previous year, according to the implemented DAX measure.

## 4. Visual Analysis 📈

- **Annual Revenue:** Compares reported revenue across years.
- **Global Vehicle Sales by Country:** Displays geographical sales using country and region mappings.
- **R&D Expenditure:** Compares research and development expenditure by year.
- **Quarterly Net Profit:** Compares quarterly profit across reporting years.
- **EBIT Trend:** Shows the trend in earnings before interest and taxes.

## 5. Interactivity 🎛️

The report includes Year and Region slicers to support interactive exploration. The visuals respond according to their configured relationships, filters, and measures.

## 6. Assumptions and Limitations ⚠️

- Financial figures must be interpreted using their stated currency and units.
- Historical and current-year figures should be validated against official publications.
- The 2022 and later geographical sales figures may use different reporting definitions.
- The implemented YoY growth calculation uses a hardcoded 2021 revenue baseline of EUR 133.9 billion for the 2022 comparison. This baseline should be validated against the exact revenue definition used in the dashboard.
- Any data transformations or calculation assumptions not explicitly recorded in the project should be verified in Power BI before being described as confirmed methodology.

## 7. Tools 🛠️

- Microsoft Power BI Desktop
- Power Query, where used
- DAX measures, where used
- Official Mercedes-Benz Group publications

## 8. Reproducibility 🔁

Download the `.pbix` file and open it in Power BI Desktop. If the report depends on external files or local file paths, those dependencies must also be supplied or the data connections updated before refresh.