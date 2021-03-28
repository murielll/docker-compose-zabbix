# Zabbix 5.2 docker compose build

This compose file was gathered from official Zabbix docker-composes and was modified to match needs of certain private project.


## Configuration

Edit following files to match your needs:

```
.env_db_pgsql
.env_web
```

Specify PosgreSQL user and password in files:

```
.POSTGRES_PASSWORD
.POSTGRES_USER
```
## Run

At the directory with ```docker-compose.yml``` run:

```
docker-compose up -d
```

To check if Zabbix run go to the ```http://localhost:8081/``` in your browser. Default login/password: Admin/zabbix.
