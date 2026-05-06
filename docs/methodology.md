# Methodology

## Objective

The objective of this project is to evaluate AI readiness across countries using selected indicators from the GAID dataset.

## Data Source

The dataset contains AI-related indicators by country, year and metric. The original structure follows a long format where each row represents one observation for a country, year and metric.

## Data Cleaning

The following steps were applied:

1. Standardized column names.
2. Converted Year to integer.
3. Converted Value to numeric.
4. Removed records without Value.
5. Removed exact duplicates.
6. Created analytical dimension and fact tables.

## Data Model

A star schema was created:

- Fact_AI_Indicators
- Dim_Country
- Dim_Year
- Dim_Metric
- Dim_Source

## AI Readiness Score

A custom score was created using five pillars:

- Economy
- Governance
- Infrastructure
- Innovation
- Talent

Each selected metric was normalized using Min-Max normalization.

## Min-Max Normalization

NormalizedValue = (Value - MinValue) / (MaxValue - MinValue) * 100

## Score Calculation

Each pillar score is calculated as the weighted average of its selected normalized metrics.

The final AI Readiness Score is calculated as the average of the five pillar scores.

## Coverage Rule

Countries with fewer than four available pillars are classified as Low coverage and excluded from the comparable global ranking.