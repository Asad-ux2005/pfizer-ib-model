# Pfizer Inc. (PFE) — Investment Banking 3-Statement Model

A fully integrated, investment banking-grade financial model for Pfizer Inc., built to bulge bracket analyst standards.

## Overview

This model covers Pfizer's financial profile across FY2019–FY2029E, incorporating the Upjohn spinoff (2020), Seagen acquisition (2023), and COVID revenue normalisation. All historical data is sourced directly from Pfizer's SEC 10-K filings via EDGAR.

## Model Structure

| Tab | Description |
|-----|-------------|
| `Executive Summary` | One-page valuation overview, DCF price, comps range, key risks & catalysts |
| `Assumptions` | All model drivers in one place — revenue growth, margins, working capital, WACC inputs |
| `Income Statement` | Fully integrated P&L, FY2021–FY2029E |
| `Balance Sheet` | Fully integrated BS, balances in every period |
| `Cash Flow Statement` | Fully integrated CFS, cash reconciles to BS in every period |
| `Working Capital` | DSO/DIO/DPO schedule, NWC rollforward |
| `Debt Schedule` | LT debt rollforward, interest expense calculation |
| `DCF` | Unlevered FCF build, WACC, Gordon Growth terminal value, sensitivity table |
| `Comps` | Trading comps vs AbbVie, Merck, BMS, Eli Lilly, J&J, AstraZeneca |
| `IS_Raw / BS_Raw / CF_Raw` | Raw historical data sourced from Pfizer 10-K filings |

## Key Outputs

- **DCF Implied Price: $59.89** (+125% upside vs $26.60 current price)
- **EV/EBITDA Comps Implied Price: $52.99** (+99% upside)
- **WACC: 5.37%** | **Terminal Growth Rate: 2.0%**
- Model fully dynamic — all projections flow from the Assumptions tab

## Methodology

- Revenue projections anchored to Wall Street consensus (FY2025E: $62.6B)
- WACC built using CAPM (Rf: 4.15%, ERP: 4.23%, β: 0.41)
- Terminal value via Gordon Growth Model
- Working capital driven by DSO/DIO/DPO day assumptions
- Debt schedule with mandatory repayment schedule ($3-4B per year)

## Formatting Conventions

- 🔵 Blue cells = hardcoded inputs
- ⚫ Black cells = formulas
- Historical periods shaded grey (FY2021–FY2024)
- Projected periods shaded blue (FY2025E–FY2029E)
- Balance check row turns green when BS balances, red if not

## Tools Used

- Microsoft Excel
- SEC EDGAR (10-K filings, FY2019–FY2024)
