# Commands

```
docker-compose run --rm -T restore psql -U postgres -h restore -Fc -w -d postgres < database_model.sql
docker-compose run --rm restore psql -U postgres -h restore -Fc -w -d postgres
```