# Сервер для трансляции и парсер

Просматривать на телевизоре можно любым клиентом torserve, например, lampamod, forkplayer.


#### Пароль админа для входа на jacket: 1234
#### Токен для jackett: yyyy1234
#### Учетная запись для torrserver: user/1234

Torrserver - сервер трансляции торрентов.
Jackett - сервер парсера

## Torrserver
### Links
[dockerhub](https://hub.docker.com/layers/asudarchikov/torrserver/latest/images/sha256-30f8a8da7d1645991068cbcbf165b7e4b0978f5f412f04c70a1895a6fbd11781?context=explore)

[github](https://github.com/YouROK/TorrServer)

[TorrServer: как смотреть торренты онлайн, habr](https://habr.com/ru/post/549704/)

[4pda](https://4pda.to/forum/index.php?showtopic=889960&st=11240)

## парсер jackett
После первого запуска в  конфиге необходимо изменить APIkey `config/Jackett/ServerConfig.json`. 
Подключиться к веб интерфейсу и добавить необходимые индексеры, установить пароль.
### Links
[Репозиторий github](https://github.com/Jackett/Jackett)

[Видео](https://www.youtube.com/watch?v=3H3NXviQ6hg)

[Docker hub](https://hub.docker.com/r/linuxserver/jackett/)
