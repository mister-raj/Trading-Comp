# Trading Comparables Valuation Model

## Overview

This project builds a **Trading Comparables valuation model** for listed Indian banking companies to estimate relative valuation and derive implied share prices using market multiples.

## Selected Publicly listed Indian banks:

* State Bank of India
* HDFC Bank
* ICICI Bank
* Axis Bank
* Kotak Mahindra Bank
* IndusInd Bank
* Bank of Baroda
* Punjab National Bank
* Canara Bank
* Union Bank of India
* Federal Bank
* IDFC First Bank

## Data Captured

### Market Data

* Current Share Price
* Shares Outstanding
* Market Capitalization
* Enterprise Value

### Financial Metrics (FY23–FY25)

* Revenue
* EBITDA
* Net Income

### Growth Metrics

* Revenue Growth
* EBITDA Growth

### Profitability

* EBITDA Margin
* Profit Margin

---

## Trading Multiples Calculated

* **EV / Revenue** → Value per ₹ of sales
* **EV / EBITDA** → Value per ₹ of operating profit
* **P / E** → Value per ₹ of net earnings

Mean and median peer multiples are computed to normalize outliers.

---

## Valuation Methodology

1. Select comparable peer group
2. Compute trading multiples
3. Derive peer mean / median benchmarks
4. Apply multiples to target company financials
5. Estimate Enterprise Value
6. Convert to Equity Value:

[
Equity\ Value = EV + Cash - Debt
]

7. Divide by shares outstanding → **Implied Share Price**

---

## Implied Valuation Outputs

The model generates valuation ranges based on:

* Minimum peer multiple
* Mean multiple
* Median multiple
* Maximum multiple

This produces a **valuation band** instead of a single point estimate.

If you want, I can:

* Expand this into a **full repo (model + memo + deck)**
* Add **formula documentation**
* Write a **case-study style report**

Just say the direction.
