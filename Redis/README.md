## Redis в контейнере.

База данных Redis подготовленная для запуска в Docker-контейнере
Больше информации - https://hub.docker.com/r/bitnami/redis/

### Требования
docker
docker-compose
redis-cli


### Установка инструментов для рабты с БД

Linux:
```sudo apt-get install redis-tools```


### Работа

Подключение:
```redis-cli -h <host> -p <port> ```
Пример:
```redis-cli -h localhost -p 6379 ```

Список команд для Редис:
https://redis.io/commands#

Например, как добавить/извлечь пару ключ:значение
https://redis.io/commands/set

