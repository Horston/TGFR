# [Онлайн-магазин Телеграмм бот](https://t.me/AllInEndTo_bot)

### Написал бота для телеграмма, в котором можно "покупать" одежду.

#### Фронтенд часть написал на react, использовал react-router-dom, написал один хук. Цвет кнопочек, продуктов использовал телеграммовские, захостил на сайте [Netlify](https://www.netlify.com/).

#### Выбрал Node.js Telegram Bot API как более новую версию API, импортировал его через require. Чтобы дебажить онлайн, создал репозиторий на гите и привязал его в netlify. Получив ссылку на приложение, вставил ее в код. Общение с ботом происходит при помощи метода Telegram.WebApp.sendData. 
#### Сделал конфигурационный файл netlify.toml с опциями для редиректов. По любому маршруту редирект в index.html.

#### Где-то не уделил внимание декомпозиции, захардкодил базу с вещами. Моей целью было изучение взаимодействия фронта и бэка с телеграммом.

#### Запускается приложение командой в консоли 
`npm start`

#### Про бэкенд написал в README репозитория с ним же (бэком). [Бэкенд часть](https://github.com/AllInEndTo/tg-bot-app-backend)