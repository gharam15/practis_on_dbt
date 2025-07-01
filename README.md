<<<<<<< HEAD
Welcome to your new dbt project!

### Using the starter project

Try running the following commands:
- dbt run
- dbt test


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](https://community.getdbt.com/) on Slack for live discussions and support
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices
=======
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
>>>>>>> 96b3f6998d5b3e33f2e665acee55c6385084658a
