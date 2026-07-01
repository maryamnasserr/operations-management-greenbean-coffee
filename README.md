# GreenBean Coffee Roasters – Forecasting and Operations Management Analysis

## Overview
This project was developed as part of the BUAD520 Operations Management for Business Informatics course (Winter 2025) at the German International University of Applied Sciences.

It analyzes demand forecasting and operational decision-making for GreenBean Coffee Roasters, a sustainable coffee production company operating in Germany and the EU. The project combines forecasting techniques, performance evaluation metrics, and strategic operations planning.

---

## Academic Information
- **University:** German International University of Applied Sciences  
- **Course:** BUAD520 Operations Management for BI  
- **Semester:** Winter 2025  
- **Student:** Maryam Nasser   

---

## Case Background
GreenBean Coffee Roasters produces and distributes three main products:
- Espresso Blend
- House Blend
- Cold Brew Bottles

The company operates in both B2B and B2C markets and focuses on sustainable production, capacity efficiency, and demand fulfillment.

---

## Project Objectives
- Forecast monthly demand using statistical methods
- Evaluate forecast accuracy using error metrics
- Support production and capacity planning decisions
- Compare forecasting techniques for operational decision-making
- Provide input for aggregate planning and strategic investment analysis

---

## Dataset Description
The dataset contains 12 months of operational and sales data for each product:

- Monthly Sales (Units)
- Forecast (Old)
- Defect Rate (%)
- Labor Hours
- Capacity Constraints
- Unit Cost and Unit Price

This dataset is used for forecasting, operational evaluation, and planning.

---

## Forecasting Methods Used

### 1. Moving Average Forecast
- Uses historical demand smoothing
- Evaluates short-term demand patterns
- Provides reactive forecasting

### 2. Linear Trend Forecast
- Captures upward/downward demand trends
- Uses regression-based trend estimation
- More stable than moving average for long-term prediction

### 3. Trend Equation Method
- Forecast model:
  `F = 1313.05 + 0.53t`
- Used to estimate demand based on time progression

---

## Forecast Evaluation Metrics

The forecasting models were evaluated using:

- Mean Absolute Deviation (MAD)
- Mean Squared Error (MSE)

### Results:
- Moving Average:
  - MAD ≈ 157.15
  - MSE ≈ 35603.49

- Linear Trend:
  - MAD ≈ 128.15
  - MSE ≈ 20863.59

### Key Insight:
The Linear Trend model performed better, showing lower error and more stable predictions compared to the Moving Average method.

---

## Operational Analysis

The forecasting results are used as input for:

- Aggregate Production Planning (Chase vs Level strategies)
- Capacity utilization decisions
- Labor and inventory planning
- Demand variability analysis

---

## Key Findings

- Demand shows noticeable variability across months
- Moving Average reacts slowly to demand shifts
- Linear Trend provides more accurate long-term forecasting
- Forecast accuracy directly impacts production planning decisions
- Stable forecasting improves cost efficiency in operations planning

---

## Business Impact

This analysis supports:
- Improved production scheduling
- Better capacity utilization
- Reduced operational inefficiencies
- More accurate strategic planning decisions

---

