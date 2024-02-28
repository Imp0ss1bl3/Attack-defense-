#Attack/Defense

1.Разорачиваем Packmate:<br>
Скачиваем <code>git clone https://gitlab.com/packmate/starter.git packmate-starter && cd packmate-starter</code>

Меняем файл `.env `:
<li>Локальный IP сервера, на который приходит игровой трафик </li>
<li>PACKMATE_LOCAL_IP=<ставим свой>  </li>
<li>Имя пользователя для web-авторизации </li>
<li>PACKMATE_WEB_LOGIN=ctf </li>
<li>Пароль для web-авторизации </li>
<li>PACKMATE_WEB_PASSWORD=Ibiza.Trusi.Cumshot </li>
<li>Интерфейс для перехвата: </li>
<li>PACKMATE_INTERFACE=<ставим свой> </li>

запускаем контейнер `sudo docker compose up -d`
