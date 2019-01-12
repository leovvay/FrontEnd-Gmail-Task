# Front End REST API GMAIL Task

## Задание:

Реализовать поиск и отображение входящих сообщений Gmail используя GmailRESTAPI

[https://developers.google.com/gmail/api/v1/reference/users/messages](https://developers.google.com/gmail/api/v1/reference/users/messages)

- Отображение информации о текущем пользователе (Правый верхний угол в макете)
- Переключение между папками сообщений в левом меню (Draft, Trash, Userlabels)
- Реализовать удаление сообщений
- Добавление и отсылку нового сообщения (&quot;Newitem&quot;)
- Локализацию сайта, в зависимости от текущего местоположения

## Требования:

- Возможно использование сторонних JS библиотек и фреймворков кроме JS препроцессоров
- Запрещено использование готовых клиентов и SDK для GmailAPI (Включая GoogleAPIClientlibraries, кроме модуля авторизации)
- Формат строки поиска аналогичен формату в Gmail search box (Например:&quot;from:someuser@example.comrfc822msgid: is:unread&quot;)

## Поддерживаемые браузеры:

- Microsoft Edge Latest version
- Firefox (Windows, Mac OS X) Latest version
- Chrome (Windows, Android, iOS, Mac OS X) Latest version
- Safari (iOS, Mac OS X)

## Требования к верстке (Если не предоставлена в задании):

- Адаптивная верстка для 3-х разрешений (Mobile 320px, Tablet 780px, Desktop 1280px)
- DOCTYPE: HTML5
- Encoding: UTF-8
- Пре-процессор для CSS (LESS или SASS)
- Возможно использование сторонних UI библиотек и фреймворков.

## Авторизация GoogleAPI:

[https://developers.google.com/api-client-library/javascript/features/authentication](https://developers.google.com/api-client-library/javascript/features/authentication)
