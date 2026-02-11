# Garmin Analytics with dbt & BigQuery

This project builds an end-to-end analytics pipeline using Garmin Connect data to analyse training load, recovery, and performance.

## Objectives
- Ingest raw Garmin Connect data via Python
- Store raw and transformed data in BigQuery
- Use dbt to build analytics-ready models
- Run quasi-experiments on training interventions
- Predict high-risk training days using statistical and ML approaches

## Tech Stack
- Garmin Connect API (Python)
- BigQuery
- dbt
- GitHub Actions
- SQL-first analytics

## Experimentation Approach
Because this is observational time-series data, experiments are treated as quasi-experiments (interrupted time series and matched control days).

## Status
Project scaffold created. Ingestion and modeling in progress.
