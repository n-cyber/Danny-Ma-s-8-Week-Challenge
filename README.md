
# 8 Week SQL Challenge

A Blend of 8 Case Studies with the application multiple SQL concepts.


## Acknowledgements

 - [Danny Ma's LinkedIN](https://www.linkedin.com/in/datawithdanny/)
 - [Data With Danny](https://www.linkedin.com/company/datawithdanny/)
 - [8 Week Challenge Page](https://8weeksqlchallenge.com/)


## Steps to set up local env for querying

[PostgreSQL Integration by Andrei Teleron](https://medium.com/analytics-vidhya/postgresql-integration-with-jupyter-notebook-deb97579a38d)

- Install ipython, sqlalchemy and DBAPI for PostgreSQL
- Load ipython-sql using the command %load_ext sql
- Import create_engine() function from sqlalchemy to use it for data connection using from sqlalchemy import create_engine
- Connect to database using %sql dialect+driver://username:password@host:port/database
- Connect to sqlalchemy using the object engine = create_engine('dialect+driver://username:password@host:port/database')
- Finally to start writing any query, just write the magic command %%sql
