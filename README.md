# Financial Analysis & Valuation of the Indian Alcoholic Beverage Sector

This repository contains a detailed financial analysis and valuation of key publicly listed companies in the Indian Alcoholic Beverage industry. The project leverages fundamental analysis and standard valuation methodologies to derive the intrinsic value of the selected companies.

---

## About The Project

This analysis was conducted to gain a deeper understanding of the financial health, risk profile, and growth prospects of major players in India's alcoholic beverage market. It combines a top-down industry overview with a bottom-up financial model for individual companies.

The core of this project is a **Discounted Cash Flow (DCF)** valuation, which estimates a company's value based on its projected future cash flows.

---

## Key Analysis Components

The analysis is structured around several key components:

-   **Industry Analysis**: A comprehensive review of the market landscape, trends, and competitive forces within the Indian alcoholic beverage sector.
-   **Risk & Return Modeling**:
    -   Calculation of **Beta** for each company using regression analysis against the NIFTY 50 index.
    -   Determination of the **Cost of Equity** using the Capital Asset Pricing Model (CAPM).
    -   Calculation of the post-tax **Cost of Debt**.
-   **Cost of Capital (WACC)**: Calculation of the Weighted Average Cost of Capital to be used as the discount rate for future cash flows.
-   **Cash Flow Forecasting**: Projection of **Free Cash Flow to the Firm (FCFF)** based on historical performance and future growth assumptions.
-   **Terminal Value & Valuation**: Calculation of the terminal value and the final implied equity value per share for each company.

---

## Repository Structure

This repository contains the following key files:

-   `Alcholic Beverage Industry.pdf`: A detailed report on the industry's landscape, key drivers, and challenges.
-   **Company Financial Models (`.csv` files)**: These files are components of a detailed financial model, likely exported from a single spreadsheet.
    -   **Company Data**: `UBL.csv`, `RADICO.csv`, `UNITEDSPR.csv` contain historical financial data for United Breweries, Radico Khaitan, and United Spirits.
    -   **Valuation Inputs**: Includes files for `Beta`, `Cost of Equity`, `Cost of Debt`, `WACC`, `Growth Rate`, and `FCFF` calculations.
    -   **Market Data**: Contains data for `NIFTY50`, Indian government bond yields (`RFR`), and other market-related inputs.

---

## Methodology

The primary valuation method used is the **Discounted Cash Flow (DCF)** model. This involves:
1.  Forecasting the company's unlevered free cash flows for a specific period.
2.  Calculating a terminal value to represent the cash flows beyond the forecast period.
3.  Discounting these future cash flows back to the present using the Weighted Average Cost of Capital (WACC).
4.  Subtracting net debt from the resulting enterprise value to arrive at the total equity value.

---

### **Disclaimer**
*This analysis is intended for educational and informational purposes only. It is not financial advice. The data and conclusions presented here should not be used for making investment decisions.*
