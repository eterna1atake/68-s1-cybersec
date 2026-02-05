# Cyber Security
## Information
- Kittitat Mukdasanit (BOSS)
- 6602041620025
- s6602041620025@email.kmutnb.ac.th


## Environment
```sh
cp env.example .env
```

## Runing a services
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