# dev-settings
Docker

```bash
docker run --rm --name django-postgres \
  -e POSTGRES_PASSWORD=#Mulalo96 \
  -e PGPORT=5432 \
  -e POSTGRES_DB=vroomhive_cardealer \
  -p 5432:5432 \
  postgres:9.6.17-alpine
```
