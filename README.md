# The Role of Risk Management Education on Livestock Risk Protection (LRP) Utilization


## Code sample (R)
Direct link: https://github.com/elnino9Milan/LRP-utilization/blob/main/LRP_utilization.Rmd

This script demonstrates:
- Data cleaning and panel data construction  
- Econometric modeling using a two-part framework (logit and fractional logit)  
- Implementation of lagged variables and robustness checks  

## Overview

This project analyzes the role of risk management education in driving the utilization of Livestock Risk Protection (LRP), a federally subsidized insurance program for U.S. feeder cattle producers. Using a two-part econometric framework, the study examines how education, subsidies, market conditions, and operation characteristics influence both the **decision to participate** and the **intensity of LRP use**.

## Research Questions

* What drives the utilization of LRP among U.S. feeder cattle producers?
* How do education workshops affect participation and usage intensity?

## Data Sources
Panel dataset created with:
* USDA Risk Management Agency (RMA): Summary of Business (SOB)
* USDA-NASS: Beef cow operations and inventory
* CME Group: Feeder Cattle Index (FCI) and price volatility
* Extension Risk Management Education (ERME): Workshop activity data

## Methodology

This study employs a **two-part model** to separately identify drivers of participation and usage intensity:

* **Extensive Margin (Participation):** Binary logit model
* **Intensive Margin (Usage Intensity):** Fractional logit model

## Key Variables
**Dependent Variable: Policy earning a premium (1, 0) at the extensive margin
**Dependent Variable: 0<Producer market share at the intensive margin
* **Main Variable of Interest:** Education workshops
* Subsidy rates
* Feeder cattle prices
* Price volatility
* Lagged participation
* Herd size
* State-by-year time trend

## Key Findings

* Education workshops significantly increase LRP participation (extensive margin), particularly in non-pilot states, but have limited impact on usage intensity.
* Subsidy rates strongly influence both participation and intensity, dominating the intensive margin across all samples.
* Evidence suggests a **substitution effect** between education and subsidy rates in driving participation.
* Education effects exhibit **temporal saturation** in pilot states, while remaining an important and growing driver in non-pilot states.

## Repository Structure

* R code – Data cleaning, econometric modeling, and robustness checks
* R code - Visualization - Producer market share by pilot and non-pilot states
* Readme file
## Tools Used

* R (data cleaning, summary statistics, econometrics, visualization)
* Excel (data organization)

## Author

Milan Chauhan
MS Agricultural Economics, University of Nebraska–Lincoln
