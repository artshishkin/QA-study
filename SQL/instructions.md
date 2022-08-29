### Инструкции по работе с SQL серверами

#### PostgreSQL

1. Запуск на локальной машине (при наличии Docker)
    - заходим в [/SQL/servers/PostgreSQL](/SQL/servers/PostgreSQL)
    - в коммандной строке запускаем
    - `docker-compose up -d`
    - в браузе переходим по ссылке
      - [http://localhost:9082](http://localhost:9082/?pgsql=postgres%3A5432&username=kate_user&db=kate_db&ns=public)
    - вводим
      - имя базы: `kate_db`
      - имя пользователя: `kate_user`
      - пароль пользователя: `kate_password`
    - работаем
2. Запуск на другой машине по локальной сети (где установлен Docker)
   - просим админа дать ссылку на сервер и параметры доступа
   - в браузе переходим по ссылке от админа
      - [http://192.168.43.9:9082](http://192.168.43.9:9082/?pgsql=postgres%3A5432&username=kate_user&db=kate_db&ns=public)
   - вводим
      - имя базы: `kate_db`
      - имя пользователя: `kate_user`
      - пароль пользователя: `kate_password`
   - работаем
3. Запуск в облачном сервере
   - админ запускает стек [PostgreSQL](/SQL/servers/PostgreSQL/docker-compose.yml) в Docker Swarm Mode
   - просим админа дать ссылку на сервер и параметры доступа
   - в браузе переходим по ссылке от админа
       - [http://ddos.shyshkin.org:9082](http://ddos.shyshkin.org:9082/?pgsql=postgres%3A5432&username=kate_user&db=kate_db&ns=public)
   - вводим
       - имя базы: `kate_db`
       - имя пользователя: `kate_user`
       - пароль пользователя: `kate_password`
   - работаем




