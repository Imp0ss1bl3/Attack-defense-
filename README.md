#Attack/Defense

1.Разорачиваем Packmate:
Скачиваем <code>git clone https://gitlab.com/packmate/starter.git packmate-starter && cd packmate-starter</code>

Меняем файл `.env `:
Локальный IP сервера, на который приходит игровой трафик \n
PACKMATE_LOCAL_IP=<ставим свой> \n
Имя пользователя для web-авторизации \n
PACKMATE_WEB_LOGIN=ctf \n
Пароль для web-авторизации \n
PACKMATE_WEB_PASSWORD=Ibiza.Trusi.Cumshot \n
Интерфейс для перехвата: \n
PACKMATE_INTERFACE=<ставим свой> \n

запускаем контейнер `sudo docker compose up -d`
