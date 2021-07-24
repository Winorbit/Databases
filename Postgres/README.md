## Redis в контейнере.

База данных PostgreSQL подготовленная для запуска в Docker-контейнере
Больше информации - https://hub.docker.com/r/bitnami/postgresql/

### Требования
docker
docker-compose

### Установка инструментов для рабты с БД

В консоли:
Linux:
```
sudo apt-get update
sudo apt-get install postgresql
```

Либо UI-клиент, например 
[PGAdmin3](https://www.pgadmin.org/download/)  Или [Dbeaver](https://dbeaver.io/)


### Работа

В консоли:
```sudo su postgres```
или
```psql -d postgres -U postgres```

