# Trading-PnL-Analysis-Kite-Python
Data analysis project to calculate, validate, and summarize trading Profit &amp; Loss (PnL) using Kite trade data and Python.
# Trading PnL Analysis

## Project Context
In trading and investment workflows, accurately tracking **Profit and Loss (PnL)** is critical for performance evaluation, risk management, and decision-making.  
Raw trade data, however, is often detailed, unstructured, and not immediately usable for insights.

This project focuses on transforming Kite trade data into a **clean, reliable PnL summary** using Python, ensuring calculations are accurate and easy to interpret.

---

## Problem Statement
Given raw trade-level data:
- How much profit or loss was made?
- Which trades contributed most to gains or losses?
- Can raw broker data be validated programmatically?

This analysis answers these questions by building a structured PnL calculation pipeline.

---

## What This Project Demonstrates
This project showcases my ability to:
- Work with real trading and financial datasets
- Clean and preprocess Excel-based data
- Apply financial logic for PnL calculation
- Validate results against summary reports
- Present results in a clear, business-friendly format

---

## Dataset Overview
The project uses:
- **Kite trade data (Excel)** containing executed trades
- Fields such as:
  - Instrument / Symbol
  - Buy & Sell quantities
  - Prices
  - Trade values
  - Transaction details

A final **PnL summary file** is generated to validate and present results.

---

## Analytical Approach

### Data Cleaning & Preparation
- Loaded Excel trade data into Python
- Handled missing and inconsistent values
- Converted numeric and date fields to correct formats
- Ensured data accuracy before calculations

### PnL Calculation Logic
- Calculated buy value and sell value per trade
- Derived Profit or Loss using trade-level logic
- Aggregated results at symbol and portfolio level
- Matched computed results with provided summary data

### Result Validation
- Cross-verified calculated PnL with summary sheet
- Ensured no mismatches in totals
- Produced a clean, reliable output ready for reporting

---

## Result Summary
- Generated accurate PnL figures from raw trade data
- Verified broker-level summary using Python
- Identified overall portfolio profit or loss
- Created a reproducible analysis pipeline for future data

---

## Key Insights
- Automated PnL calculation reduces manual errors
- Trade-level aggregation provides transparency into performance
- Python-based validation builds confidence in financial reports
- This approach can scale to daily or monthly trading data

---

## Tools & Skills Used
- Python
- Pandas – data cleaning, aggregation, and calculations
- NumPy – numerical operations
- Excel data handling
- Financial data analysis
- Result validation and reconciliation

---
