#### Microsoft SQL Server

1. Запуск на локальной машине (при наличии Docker)
    - заходим в [/SQL/servers/MicrosoftSQL](/SQL/servers/MicrosoftSQL)
    - в коммандной строке запускаем
    - `docker-compose up -d`
    - в браузе переходим по ссылке
        - [http://localhost:9082](http://localhost:9082/?mssql=ms_sql%3A1433&username=sa)
    - вводим
        - имя базы: ``
        - имя пользователя: `sa`
        - пароль пользователя: `kate_Pa55w0rd`
    - работаем
2. Запуск на другой машине по локальной сети (где установлен Docker)
    - просим админа дать ссылку на сервер и параметры доступа
    - в браузе переходим по ссылке от админа
        - [http://192.168.43.9:9082](http://192.168.43.9:9082/?mssql=ms_sql%3A1433&username=sa)
    - вводим
        - имя базы: ``
        - имя пользователя: `sa`
        - пароль пользователя: `kate_Pa55w0rd`
    - работаем
3. Запуск в облачном сервере
    - админ запускает стек [MicrosoftSQL](/SQL/servers/MicrosoftSQL/docker-compose.yml) в Docker Swarm Mode
    - просим админа дать ссылку на сервер и параметры доступа
    - в браузе переходим по ссылке от админа
        - [http://ddos.shyshkin.org:9082](http://ddos.shyshkin.org:9082/?mssql=ms_sql%3A1433&username=sa)
    - вводим
        - имя базы: ``
        - имя пользователя: `sa`
        - пароль пользователя: `kate_Pa55w0rd`
    - работаем




