# postgresql-data-dump
A dummy PostgreSQL database

Useful for tests with low cardinality indexes.

## Usage

Unzip data dump
```bash
unzip init.sql.zip
```

Run PostgreSQL 
```bash
docker-compose up --renew-anon-volumes
```

Set up a connection with your favorite PostgreSQL client with the following credentials:
```bash
host: 127.0.0.1:5432
username: `emiliosp`
password: `emiliosp`
database: `measurements`
```

<a href="https://www.buymeacoffee.com/emiliosp" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
