# telegram_weather_bot

## Этот бот предназначен для того, чтобы показывапть погоду в городах

## Установка зависимостей
* Регистрируемся на сайте погоды https://openweathermap.org/, получаем ключ API
* Получаем токен и создаем нового бота через @BotFather в телеграме коммандой "/newbot"
* Установить pyowm (В командной строке от имени администратора вводим: `pip install pyowm` )
* Установить pyTelegramBotAPI (`pip install pyTelegramBotAPI`)
* Либо ставим все зависимости через `pip install -r requirements.txt`
* В файл `config.py` вставляем свои данные `open_weather_token` = `efadsdgjhmewargthftjkmiuwyrhed` (example)
* `tg_bot_token` = `rwstygerthye5435346-sfhdy546` (example)

### Запуск бота
* Пишем боту команду `/start` далее пишем город в котором хотим узнать погоду
* Бот присылает нам данные о погоду
