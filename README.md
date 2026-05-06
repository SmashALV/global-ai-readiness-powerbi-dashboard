# Global AI Readiness & Growth Analytics Dashboard

## Project Overview

This project analyzes global AI readiness indicators using Python, Power BI and DAX.

## Business Problem

Governments, companies and researchers need to understand which countries are better prepared to adopt, govern and scale artificial intelligence.

## Objectives

- Build a clean analytical model.
- Compare AI readiness across countries.
- Benchmark Latin America.
- Analyze Peru's position.
- Create a Power BI dashboard.
- Document a reproducible data analytics workflow.

## Dataset

Dataset: GAID Master AI Data Compilation  
Rows after cleaning: 259,398  
Countries: 227  
Year range: 1998–2025

## Tools

- Python
- pandas
- Power BI
- Power Query
- DAX
- GitHub

## Data Pipeline

Raw CSV → Data Cleaning → Star Schema → AI Readiness Score → Power BI Dashboard

## Data Model

Insert image:

![Data Model](images/data_model.png)

## Dashboard Preview

![Executive Overview](images/executive_overview.png)

![Latin America Benchmark](images/latin_america_benchmark.png)

## AI Readiness Score

The custom AI Readiness Score was calculated using five pillars:

- Economy
- Governance
- Infrastructure
- Innovation
- Talent

Countries with fewer than four pillars were excluded from the comparable ranking.

## Key Insights

1. AI readiness is concentrated in a small group of leading economies.
2. Latin America shows a moderate readiness level.
3. Peru has complete data coverage for the selected model.
4. Peru remains behind regional leaders such as Uruguay, Brazil and Chile.
5. Data coverage must be controlled to avoid biased rankings.

## Repository Structure

Explain folders.

## How to Run

1. Clone the repository.
2. Install dependencies.
3. Add raw dataset to data/raw.
4. Run notebooks.
5. Open Power BI file.

## Author

Jose Bustillos  
LinkedIn: www.linkedin.com/in/josefabrizziobustillos
GitHub: https://github.com/SmashALV
