# Stock Market Analytics Dashboard

A stock analytics project covering 10 NSE Listed stocks across FMCG, Energy, Auto, Banking, Finance, and IT — built with Python, SQL, and Power BI.

**Live Dashboard:** [View on Power BI]([YOUR_POWERBI_LINK_HERE](https://app.powerbi.com/view?r=eyJrIjoiNmQ0ZWU2YzMtMjFjNi00NGY4LWE3OWMtMmFmYjNkNWIwNjc2IiwidCI6Ijg0Yjg5MWVhLTM4ZjMtNGRhMy1hMmNhLTE1ODA3MjEwZTc4NCJ9))

## About

We have pulled six years of daily price data (1 Jan 2020 – 4 June 2026) for 10 stocks — Adani Enterprises, Bajaj Finance, HDFC Bank, Hindustan Unilever, Infosys, ITC, Maruti Suzuki, Reliance, SBI, and TCS — using the yfinance API in Google Colab using python, cleaned using pandas and queried with SQL, and built a 3-page interactive Power BI report on top of it.

## Tech stack

- **Python (Google Colab)** — yfinance for Data extraction, Pandas for Data cleaning
- **SQL** — Querying, Aggregation, Calculated metrics
- **Power BI** — Dashboarding, DAX measures, Interactive filtering by ticker and date range

## The 3 pages

**1. Stocks Analytics Dashboard** — Overview of Latest, Maximum, Minimum and Average closing prices across all 10 stocks, daily returns split by sector, and a high-low range area
