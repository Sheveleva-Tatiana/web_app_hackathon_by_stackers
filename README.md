# new_year_app

### Запуск из папки traffic_app
#### В папке создать файл .env и определить в нем значения
```
DB_USER=
DB_PASS=
DB_PORT=
DB_NAME=
DB_HOST=
HOST=<Адрес хоста приложения>
EMAIL_HOST=
EMAIL_PORT=
EMAIL_HOST_USER=
EMAIL_HOST_PASSWORD=
EMAIL_USE_TLS=
```
#### Запуск 
```
docker build -t new_year .
docker run -p8000:8000 new_year
```
#### Пройдите на https://localhost:8000

* Добавьте на сайте администратора мероприятие. 
* Отправьте сгенерированную ссылку желающим посетить мероприятие. 
* Участники мероприятия переходят по ссылке и регистрируются в форме. 
* Его данные появятся в базе данных. 
* После регистрации отсканируйте у участника qr код - теперь будет отмечено, что он посетил мероприятие. 
