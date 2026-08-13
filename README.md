# Indian Pharmaceuticals | Comparable Company Valuation

## Project Overview

This project presents a **Comparable Company Analysis (CCA)** of selected publicly listed Indian pharmaceutical companies to assess relative valuation and derive an **implied equity value and implied value per share** using market-based valuation multiples.

The analysis follows a structured relative valuation approach by identifying an appropriate peer universe, benchmarking companies across key trading multiples, analysing the distribution of peer valuations, and applying selected multiples to derive an implied valuation.

The objective is to evaluate whether the target company appears **overvalued or undervalued relative to its comparable peer group**.

## Project File 

[ View Full Project Report](<Indian Pharmaceuticals – Comparable Company Valuation.xlxs>) 

The Excel model contains the peer universe, financial data, trading multiples, peer statistics, implied valuation calculations and overvaluation/undervaluation assessment.
---

## Valuation Universe

The comparable universe consists of Indian listed pharmaceutical companies selected based on similarities in:

* Industry and business operations
* Product and therapeutic exposure
* Revenue and earnings profile
* Scale of operations
* Capital market presence
* Availability of comparable financial and market data

### Comparable Companies

* Cipla Limited
* Sun Pharmaceutical Industries Limited
* Divi's Laboratories Limited
* Torrent Pharmaceuticals Limited
* Zydus Lifesciences Limited
* Lupin Limited
* Dr. Reddy's Laboratories Limited
* Mankind Pharma Limited
* Laurus Labs Limited
* Aurobindo Pharma Limited

---

## Data Source

Financial and market data used in the analysis was sourced from **Screener.com**.

The dataset includes key inputs required for relative valuation, including:

* Share Price
* Shares Outstanding
* Equity Value / Market Capitalisation
* Net Debt
* Enterprise Value
* Revenue
* EBITDA
* Net Income

The financial data was standardised across the peer universe before calculating valuation multiples.

---

## Valuation Methodology

### 1. Comparable Company Selection

A peer universe of listed Indian pharmaceutical companies was identified based on business similarity and financial comparability.

This provides a relevant market benchmark against which the target company's valuation can be assessed.

### 2. Enterprise Value and Equity Value Analysis

Enterprise Value was considered alongside Equity Value to account for differences in capital structure across comparable companies.

The relationship used is:

**Enterprise Value = Equity Value + Net Debt**

Where a company has net cash, Net Debt may be negative, thereby reducing Enterprise Value relative to Equity Value.

---

## Trading Multiples

Three commonly used valuation multiples were calculated for each comparable company.

### EV / Revenue

**EV / Revenue = Enterprise Value / Revenue**

This multiple compares the total value of a company's operations with its revenue base and is useful for comparing businesses where profitability levels may differ.

### EV / EBITDA

**EV / EBITDA = Enterprise Value / EBITDA**

EV/EBITDA measures the value of the underlying business relative to its operating earnings before depreciation, amortisation, interest and taxes.

It provides a capital structure-neutral basis for comparing operating valuations across companies.

### Price / Earnings

**P/E = Equity Value / Net Income**

Alternatively:

**P/E = Share Price / Earnings Per Share**

The P/E multiple evaluates the value attributable to equity shareholders relative to the company's earnings.

---

## Peer Multiple Analysis

After calculating the trading multiples for each company, the distribution of the peer group was analysed using the following statistical measures:

| Statistic           | Purpose                                      |
| ------------------- | -------------------------------------------- |
| **High**            | Maximum observed trading multiple            |
| **75th Percentile** | Upper-quartile valuation benchmark           |
| **Average**         | Mean valuation of the peer universe          |
| **Median**          | Mid-point of the peer valuation distribution |
| **25th Percentile** | Lower-quartile valuation benchmark           |
| **Low**             | Minimum observed trading multiple            |

Excel functions including **MAX, MIN, QUARTILE, AVERAGE and MEDIAN** were used to calculate the respective benchmarks.

Using multiple statistical measures helps identify the valuation range across the peer group and reduces reliance on any single comparable company.

---

## Implied Valuation

Selected peer trading multiples were applied to the target company's corresponding financial metrics to estimate its implied valuation.

### Enterprise Value Based Multiples

For EV/Revenue:

**Implied Enterprise Value = Selected EV/Revenue Multiple × Target Revenue**

For EV/EBITDA:

**Implied Enterprise Value = Selected EV/EBITDA Multiple × Target EBITDA**

The resulting Enterprise Value was converted into Equity Value using:

**Implied Equity Value = Implied Enterprise Value − Net Debt**

The implied value attributable to each share was then calculated as:

**Implied Value per Share = Implied Equity Value / Shares Outstanding**

### P/E Based Valuation

For the P/E methodology:

**Implied Equity Value = Selected P/E Multiple × Target Net Income**

and:

**Implied Value per Share = Implied Equity Value / Shares Outstanding**

Because P/E is an equity value multiple, an Enterprise Value to Equity Value bridge is not required.

---

## Valuation Assessment

The implied value per share derived from the comparable company analysis was compared with the company's prevailing market price.

The valuation interpretation is:

**Implied Value per Share > Current Share Price**
→ Potentially **Undervalued**

**Implied Value per Share < Current Share Price**
→ Potentially **Overvalued**

**Implied Value per Share ≈ Current Share Price**
→ Potentially **Fairly Valued**

This provides a market-based perspective on whether the company's current trading valuation is justified relative to its peers.

---

## Key Analysis Performed

* Identified and screened an appropriate **comparable company universe**
* Collected and standardised financial and market data
* Analysed **Enterprise Value, Equity Value and Net Debt**
* Calculated **EV/Revenue, EV/EBITDA and P/E multiples**
* Evaluated peer valuation dispersion using **High, Low, 75th Percentile, 25th Percentile, Average and Median**
* Derived **Implied Enterprise Value**
* Bridged Enterprise Value to **Implied Equity Value**
* Calculated **Implied Value per Share**
* Benchmarked implied valuation against the prevailing market price
* Assessed potential **overvaluation or undervaluation**
* Built the analysis in Microsoft Excel using a structured financial modelling approach

---

## Skills Demonstrated

**Financial Analysis**

* Comparable Company Analysis
* Relative Valuation
* Financial Statement Analysis
* Market Benchmarking
* Peer Analysis

**Valuation**

* Enterprise Value
* Equity Value
* EV/Revenue
* EV/EBITDA
* P/E
* Implied Equity Value
* Implied Share Price
* Valuation Range Analysis

**Financial Modelling**

* Enterprise Value to Equity Value Bridge
* Trading Multiple Analysis
* Valuation Benchmarking
* Scenario-Based Valuation
* Statistical Analysis of Peer Multiples

**Microsoft Excel**

* MAX
* MIN
* QUARTILE
* MEDIAN
* AVERAGE
* Financial Modelling
* Structured Valuation Analysis

---

## Key Takeaway

The project demonstrates how **public market trading multiples can be used to benchmark a company against comparable businesses and derive an implied valuation range**.

Rather than relying on a single valuation multiple, the analysis considers multiple operating and equity-based metrics and evaluates valuation across different points of the peer distribution. This provides a more comprehensive view of the target company's relative market positioning.

---

## Limitations

Comparable Company Analysis is dependent on the quality and relevance of the selected peer universe. Differences in business mix, growth expectations, margins, capital structure, geographic exposure and risk profiles can result in materially different trading multiples.

The analysis therefore represents a **relative market valuation framework rather than an intrinsic valuation** and should ideally be considered alongside methodologies such as Discounted Cash Flow analysis and precedent transaction analysis.

---

## Tools & Sources

* **Microsoft Excel**: Financial modelling and valuation analysis
* **Screener.com**: Financial and market data
* **NSE**: Company ticker identification and market reference

---

## Disclaimer

This project has been independently prepared for educational and portfolio purposes. It does not constitute investment research, investment advice, or a recommendation to buy or sell any security.
