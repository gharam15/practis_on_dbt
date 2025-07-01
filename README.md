# practis_on_dbt

This is a dbt project configured to work with PostgreSQL on Windows.

## Environment Setup

Create and activate a virtual environment:
```bash
python -m venv dbt-env
dbt-env\Scripts\activate

Install dbt-core:
pip install dbt-core

Start PostgreSQL CLI
cd "C:\Program Files\PostgreSQL\14\bin"
.\psql -U postgres

Create the database:
CREATE DATABASE postgresdb;

Initialize dbt project
dbt init dbt-postgres_project
