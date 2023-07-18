# postgres-cheatsheet
## Dump
```
pg_dump -h localhost -U postgres -p 6185 -d database_name > dump.sql
```
## Restore
```
psql -U postgres -W -d database_name -f dump.sql
```
