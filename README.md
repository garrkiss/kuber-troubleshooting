# Домашнее задание к занятию "`Troubleshooting`" - `Бакулев Евгений`

## Задание. При деплое приложение web-consumer не может подключиться к auth-db. Необходимо это исправить


Ошибка при деплое, отсутствовали нужные namespaces. Создал
![Ссылка](https://github.com/garrkiss/kuber-troubleshooting/blob/main/img/1.png)

В логах пода были ошибки
![Ссылка](https://github.com/garrkiss/kuber-troubleshooting/blob/main/img/2.png)

Исправил деплоймент добавив .data
![Ссылка](https://github.com/garrkiss/kuber-troubleshooting/blob/main/img/3.png)

Проверил логи, работает
![Ссылка](https://github.com/garrkiss/kuber-troubleshooting/blob/main/img/4.png)