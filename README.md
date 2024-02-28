#Attack/Defense

1.Разорачиваем Packmate:<br>
Скачиваем <code>git clone https://gitlab.com/packmate/starter.git packmate-starter && cd packmate-starter</code>

Меняем файл `.env `:
<br>
<li>Локальный IP сервера, на который приходит игровой трафик </li>
PACKMATE_LOCAL_IP=<ставим свой>
<li>Имя пользователя для web-авторизации </li>
PACKMATE_WEB_LOGIN=ctf
<li>Пароль для web-авторизации </li>
PACKMATE_WEB_PASSWORD=Ibiza.Trusi.Cumshot
<li>Интерфейс для перехвата: </li>
PACKMATE_INTERFACE=<ставим свой> 
<br><br>
запускаем контейнер <code>sudo docker compose up -d</code>
