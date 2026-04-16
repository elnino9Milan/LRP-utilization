# Education Drives Livestock Risk Protection Utilization 

## Overview

This project analyzes the role of continued risk management education on Livestock Risk Protection (LRP), a federally subsidized insurance tool for US feeder cattle producers using a two-part econometric framework. The goal is to understand how education, subsidies, market conditions, and production factors influence both the extensive (participation) and intensity of LRP usage (intensive margins).

## Research Question

* What drives the utilization of LRP among US feeder cattle producers?
* How do education workshops impact LRP participation and the insurance usage intensity?

## Data and Sources

* Summary of Business (SOB): USDA Risk Management Agency (RMA)
* Beef-cow operations, beef-cow inventory: USDA-NASS
* Feeder cattle index (FCI), and feeder cattle price volatility: CME Group 
* Days of completed workshops on feeder cattle LRP: by Extension Risk Management Education (ERME)

## Methodology

This study uses a **two-part model**:

1. **Extensive Margin (Participation)** – Binary logit model
2. **Intensive Margin (Usage intensity)** – Fractional logit model

## Key Variables
* Producer market share = Dependent variable (DV)
* Education workshops = Explanatory variable of interest
* Subsidy rates
* Feeder cattle prices
* Feeder cattle price volatility
* Lagged DV
* State by Year time trend

## Key Insights

* Education programs increase LRP participation
* Subsidy changes significantly affect adoption
* Strong persistence in participation behavior

## Files

* `two part fractional model - JAAE.Rmd`: Main analysis script

## Tools Used

* R (econometrics, data cleaning, visualization)

## Author

Milan Chauhan
MS Agricultural Economics, University of Nebraska–Lincoln
