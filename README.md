<head>Attack-defense</head>

1.Разорачиваем Packmate:
Скачиваем <code>git clone https://gitlab.com/packmate/starter.git packmate-starter && cd packmate-starter</code>
Меняем файл `.env `:
<code>
# Локальный IP сервера, на который приходит игровой трафик
PACKMATE_LOCAL_IP=<ставим свой>
# Имя пользователя для web-авторизации
PACKMATE_WEB_LOGIN=ctf
# Пароль для web-авторизации
PACKMATE_WEB_PASSWORD=Ibiza.Trusi.Cumshot
# Интерфейс для перехвата:
PACKMATE_INTERFACE=<ставим свой>
</code>
запускаем контейнер `sudo docker compose up -d`
