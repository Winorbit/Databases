## CouchDB в контейнере.

База данных CouchDB подготовленная для запуска в Docker-контейнере
Больше информации - https://hub.docker.com/r/bitnami/couchdb/


### Требования
docker
docker-compose

### Запуск

C выводм данных в консоль - ```docker-compose up --build```
В фоновом режиме - ```docker-compose up --build -d```


### Работа
user - admin
password - couchdb

Корень - http://127.0.0.1:5984/
Панель управления - http://127.0.0.1:5984/_utils/