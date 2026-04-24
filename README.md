# Euro Fixed Income Monitor

This project is a Python-based monitoring tool for euro fixed income markets. It focuses on money market conditions, yield curve dynamics, and bond sensitivity analysis using official ECB data.

## Project Overview

The notebook combines three core areas of fixed income market analysis:

- Money market monitoring through `€STR` and the ECB deposit facility rate
- Yield curve analysis using euro area AAA government bond spot rates
- Bond sensitivity analysis using a real German Bund and a simple duration framework

## Data Used

The project uses official ECB data exported as CSV files:

- `€STR`
- `ECB Deposit Facility Rate (DFR)`
- `2Y AAA yield curve spot rate`
- `5Y AAA yield curve spot rate`
- `10Y AAA yield curve spot rate`
- `30Y AAA yield curve spot rate`

## Key Features

- Cleaning and merging multiple ECB time series into one market dataset
- Computing daily yield changes in basis points
- Tracking the `2s10s` curve slope
- Comparing `€STR` with the ECB deposit facility rate
- Plotting the latest euro area AAA yield curve
- Generating a short rule-based market commentary
- Estimating bond price sensitivity to a `+10 bps` rate shock
- Computing Macaulay duration and modified duration for a real German Bund

## Main Outputs

The notebook produces:

- A latest market dashboard
- A yield curve chart across key maturities
- A `2s10s` slope chart
- A daily yield changes chart in basis points
- A money market chart comparing `€STR` and `DFR`
- A bond sensitivity and duration analysis

## Bond Case Study

For the bond sensitivity section, I used a real German Bund as a simple case study. This helped connect the market data analysis to a practical fixed income application through bond pricing, yield shocks, and duration.

## Tools

- Python
- pandas
- matplotlib
- Google Colab

## How to Run

1. Open the notebook in Google Colab
2. Upload the ECB CSV files used in the project
3. Run the notebook from top to bottom

## Project Motivation

I built this project to strengthen both my Python skills and my understanding of euro fixed income markets, with a focus on practical market monitoring rather than overly complex quantitative modelling.
Author : Joshua Lemiere Mac Douglas – Master in Finance Contact: Joshuamacdouglas@gmail.com
