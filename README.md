# Dagster Sample Project
This repo is a sample analytics engineering project.

- Source Resource is a local instance of Microsoft SQL Server Express.
- Source Data is the AdventureWorksDW data warehouse sample database.
- Destination Resouce is a local sqlite backed ducklake metadata catalog.
- Destination data is local parquet datalake.

## Tech Stack
- Project Dependancy Management via [uv](https://astral.sh/uv) by Astral
- Project linting and formatting via [ruff](https://astral.sh/ruff)
- Data Ingestion with [dlt](https://dlthub.com) via `dagster-dlt`
- Data Modeling with [dbt](https://www.getdbt.com) via `dagster-dbt`
- Data Orchestration with [Dagster](https://dagster.io) via `create-dagster@latest project`