
dbt Marketing Data Pipeline

Overview
This project builds an end-to-end data pipeline using dbt and BigQuery to analyze marketing campaign performance.

# Architecture

The project follows a layered dbt structure:

Staging Layer → Cleans raw data
Intermediate Layer → Combines and enriches data
Mart Layer → Produces final business metrics

# Data Sources

- Meta Ads data
- Google Ads data
- Conversions data


# Key Metrics

- Total Spend
- Total Revenue
- ROAS (Return on Ad Spend)


# Tech Stack

- dbt Cloud
- Google BigQuery
- SQL
- YAML

# Features

- Multi-source data integration
- Modular dbt architecture
- Data transformation and cleaning
- Data quality tests using dbt


# Example Analysis

The final model provides campaign-level insights such as:
- Top performing campaigns
- Underperforming ads
- Platform comparison (Meta vs Google)

# Project Structure
models/
   staging/
   intermediate/
   marts/

   
# How to Run the Project

1. Load raw data into BigQuery tables
2. Open dbt Cloud project
3. Run: dbt build

# Key Insights

Identify top-performing campaigns
Compare Meta vs Google performance
Detect campaigns with low ROI
Monitor marketing spend efficiency  


   
