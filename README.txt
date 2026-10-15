# Week 1 Data Engineering Lab

## Scenario
A small online shop sends daily order data as a CSV file. A manager wants a reliable summary of valid orders by city.

## Pipeline plan
- Source: `orders.csv` (daily batch file)
- Raw destination: BigQuery table `de_intro.raw_orders`
- Curated output: query results after checking and filtering the data
- User of the output: shop manager

## Local data check
Before reporting, record at least two issues you found in the CSV and what you recommend doing with each.

1. Issue and recommendation: there is a duplicated values 0-1006
2. Issue and recommendation: there is a null value in costumer city for order o-1004

## What the pipeline does
Complete after the lab: In one sentence, describe how the data moves from the source to a useful output.


Question 1: What problems could make the report inaccurate?

-Bad data: outdated, biased, incomplete, or unreliable sources.
-Small or unrepresentative samples: results don’t apply to the whole population.
-Calculation errors: wrong formulas, double counting, typos...