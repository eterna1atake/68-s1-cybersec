# Cyber Security
## Information
- Kittitat Mukdasanit (BOSS)
- 6602041620025
- s6602041620025@email.kmutnb.ac.th


## Environment
```sh
cp env.example .env
```

## Running a services
### Database 
```
docker compose -f db.yaml up #monotoring
docker compose -f db.yaml up -d #background daemon
```

### Postgres admin 
```
docker compose -f admin.yaml up #monotoring
docker compose -f admin.yaml up -d #background daemon
```


### Strapi Application 
```
docker compose -f app.yaml up #monotoring
docker compose -f app.yaml up -d #background daemon
```

### Running 3 services in one line (etg.Database, PG Admin, Strapi)

```
docker-compose up #monotoring
docker-compose up -d #background daemon
```