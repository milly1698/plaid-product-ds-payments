# Payments Funnel Intelligence (Product Data Science)

## Overview
This project demonstrates a fintech Product Data Science workflow inspired by Plaid.

### What this project does
- Pulls transactions from Plaid Sandbox
- Builds a payment funnel (verified → authorized → completed)
- Runs an A/B experiment
- Identifies signals driving transfer failures

## Data
- Source: Plaid Sandbox (test data only)
- No real customer data used

## Methods
- Funnel analytics
- A/B testing
- Feature importance analysis

## Key Insights
- Simplified flow improves completion rate
- High retries and high transaction amounts increase failures
- Bank friction signals strongly affect conversion

## How to run
Open the notebook in Google Colab and run all cells.
