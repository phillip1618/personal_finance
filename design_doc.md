# Design Document

## Functionality

- Create a new Google Sheet within the Finance statements directory, automatically filling in the transactions. Perhaps we could also use machine learning to autofill the transaction categories based on the transaction historical data.
- Set up a database of financial data, which contains information from my Capital One account
- Have a PowerBI dashboard display all high-level financial data, which may include current amounts of different accounts and the projection of the amounts over the course of many years. Some accounts we want to consider are:
  - 401K information
  - ROTH IRA information
  - Financial goals information

## Technologies

- Languages: Python
- Dashboarding: PowerBI
- Database: dbt, PostgresQL
- Infrastructure: Docker, GitHub Actions(?), Azure DevOps(?), Talend(?)
