# mcdonalds-financial-health-dashboard
Power BI dashboard analyzing McDonald's financial statements (2021-2024) with time-series forecasting.
# McDonald's Financial Health & Forecasting Dashboard (2021–2024)

## Project Overview
An end-to-end financial analytics solution built in Power BI to analyze McDonald's fiscal statement metrics (2021–2024) and generate trend-based future forecasts.

![Dashboard Preview](dashboard_preview.png)

## Key Technical Achievements
- **ETL & Data Transformation:** Cleaned wide-format financial datasets via Power Query, unpivoted year attributes, handled currency formatting, and coerced line items into Decimal types.
- **Data Modeling:** Built a contiguous `Dim_Date` table using DAX to construct clean 1-to-many dynamic relationships with financial statement metrics.
- **DAX Calculations:** Developed core business measures including `Total Revenue`, `Operating Income`, `Net Income`, and `Profit Margin %`.
- **Visual Analytics & Forecasting:** Designed an interactive Income Statement Matrix View alongside time-series Line Charts featuring predictive forecasting for upcoming fiscal periods.

## Dashboard Features
- Interactive Matrix view for multi-year financial statements.
- Dynamic line trend visual with built-in predictive analytics (3-year forecasting horizon).
- Consolidated executive summary KPI views.
