# AsterChem GHG Accounting Model

## Project Overview

This project is a formula-driven greenhouse gas (GHG) accounting model developed in Microsoft Excel for a hypothetical specialty chemical manufacturer named **AsterChem Specialty Chemicals Ltd.**

The workbook calculates and analyses:

* Scope 1 emissions
* Scope 2 emissions using both location-based and market-based methods
* All 15 Scope 3 categories
* Total organizational GHG inventory
* Scope 3 category contributions
* Production-based emissions intensity
* Revenue-based emissions intensity
* Reconciliation and percentage checks

The project demonstrates the use of Excel for carbon accounting, emission-factor mapping, emissions calculations, category analysis, and sustainability reporting.

## Important Disclaimer

> **AsterChem Specialty Chemicals Ltd., its manufacturing facilities, activity data, operational records, contractual instruments, and emission factors are entirely fictional and synthetic.**

The data were created exclusively for educational and portfolio purposes. The workbook is not a verified corporate GHG inventory and should not be used for regulatory reporting, investment decisions, assurance activities, or operational decision-making.

All emission factors must be replaced with authoritative factors suitable for the relevant reporting year, geography, activity, technology, and reporting framework before the model is used for a real organization.

## Project Objectives

The main objectives of this project were to:

* Understand the structure of a corporate GHG inventory
* Classify emission sources under Scope 1, Scope 2, and Scope 3
* Apply emission factors to different types of activity data
* Calculate Scope 2 emissions using location-based and market-based methods
* Represent and analyse all 15 Scope 3 categories
* Develop traceable and formula-driven Excel calculations
* Calculate emissions-intensity indicators
* Create reconciliation checks for important totals and percentages
* Present the results through a consolidated GHG summary

## Organizational Boundary

The model uses the **operational control approach**.

The fictional organization consists of three manufacturing facilities:

* **Northport Plant**, United Kingdom
* **Rheinhafen Plant**, Germany
* **Riverbend Plant**, United States

The reporting period is the **2025 calendar year**.

## Workbook Structure

| Worksheet          | Description                                                                                                                 |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| `GHG Summary`      | Presents the major emissions results, inventory totals, Scope 2 comparison, intensity indicators, and largest contributors. |
| `Company Data`     | Contains the fictional company profile, reporting boundary, revenue, employees, facilities, and production data.            |
| `Scope 1 Data`     | Calculates direct emissions from sources controlled by the company.                                                         |
| `Scope 2 Data`     | Calculates purchased-energy emissions using location-based and market-based methods.                                        |
| `Scope 3 Data`     | Calculates value-chain emissions and summarises all 15 Scope 3 categories.                                                  |
| `Emission Factors` | Contains the synthetic emission-factor lookup table.                                                                        |
| `Data Notes`       | Documents the dataset design, organizational boundary, assumptions, exclusions, and limitations.                            |

## Scope 1 Coverage

Scope 1 includes direct emissions from sources owned or controlled by the fictional company:

* Stationary combustion from natural gas
* Mobile combustion from diesel and LPG
* Process emissions from chemical manufacturing
* Fugitive emissions from refrigerant leakage

The general calculation used is:

```text
Emissions (tCO2e) = Activity data × Emission factor ÷ 1,000
```

The division by 1,000 converts kilograms of carbon dioxide equivalent into tonnes of carbon dioxide equivalent when the emission factor is expressed in kilograms of CO2e per activity unit.

## Scope 2 Coverage

Scope 2 covers emissions associated with purchased electricity and purchased steam.

The workbook reports Scope 2 emissions using two methods:

* **Location-based method:** Uses synthetic regional grid emission factors.
* **Market-based method:** Uses synthetic contractual or supplier-specific emission factors.

The workbook also calculates the absolute and percentage difference between the location-based and market-based results.

## Scope 3 Coverage

The workbook represents all 15 Scope 3 categories:

1. Purchased goods and services
2. Capital goods
3. Fuel- and energy-related activities
4. Upstream transportation and distribution
5. Waste generated in operations
6. Business travel
7. Employee commuting
8. Upstream leased assets
9. Downstream transportation and distribution
10. Processing of sold products
11. Use of sold products
12. End-of-life treatment of sold products
13. Downstream leased assets
14. Franchises
15. Investments

Category 8, **Upstream leased assets**, is treated as not applicable because the relevant leased assets are assumed to be inside the operational boundary and already accounted for under Scope 1 and Scope 2.

## Excel Functions and Techniques Used

The workbook uses the following Excel functions and modelling techniques:

* `VLOOKUP` for retrieving emission factors
* `SUM` for calculating emissions totals
* `SUMIF` for category-level aggregation
* `IF` for inclusion and exclusion logic
* `INDEX` and `MATCH` for identifying the largest Scope 3 category
* Absolute and mixed cell references
* Percentage calculations
* Unit conversions
* Cross-sheet formula links
* Reconciliation checks
* Emissions-intensity calculations

## Skills Demonstrated

This project demonstrates skills in:

* Corporate GHG accounting
* Carbon-footprint calculation
* Scope 1, Scope 2, and Scope 3 classification
* Operational-boundary determination
* Emission-factor mapping
* Excel formula development
* Data validation and reconciliation
* Sustainability data analysis
* Emissions-intensity analysis
* Technical documentation
* Transparent reporting of assumptions and limitations

## Limitations

* All company and activity information is fictional.
* All emission factors are synthetic and illustrative.
* The workbook has not undergone third-party verification or assurance.
* The model does not include uncertainty analysis.
* Supplier-specific product carbon footprints are not included.
* Spend-based and downstream emission factors are simplified proxies.
* Offsets, avoided emissions, carbon removals, and biogenic carbon are excluded.
* The model does not establish compliance with the GHG Protocol, ISO 14064-1, CDP, CSRD, ESRS, or any regulatory reporting requirement.
* The project demonstrates accounting and Excel-modelling logic rather than a verified real-company carbon footprint.

## Author

Developed by **Rohith Sajish Babu** as an educational and portfolio project focusing on GHG accounting, sustainability analysis, and Excel modelling.

