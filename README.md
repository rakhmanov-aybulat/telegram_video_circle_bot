# Telegram-Video-Circle-Bot
Этот проект представляет собой открытый код бота для Telegram, который преобразует видео, отправленное пользователем, в видеокружок (круглое видео).

## Установка
1. Клонируйте репозиторий:
``` git clone https://github.com/yourusername/Telegram-Video-Circle-Bot.git ```

2. Перейдите в директорию проекта:
``` cd telegram-video-circle-bot ```

3. Установите необходимые зависимости:
``` pip install -r requirements.txt ```

## Настройка
* Откройте файл bot.py и замените API_TOKEN на ваш токен API от BotFather.

## Запуск

1. Запустите бота:
``` python bot.py ```

## Использование
1. Откройте Telegram и найдите вашего бота по имени, которое вы указали при создании бота в BotFather.
   
3. Отправьте команду `/start` боту.
   
5. Отправьте видео, которое вы хотите преобразовать в круглое.
   
7. Бот скачает видео, преобразует его в круглое и отправит обратно вам.

## Структура проекта
* `bot.py`: основной файл с кодом бота.
* `requirements.txt`: файл с необходимыми для работы бота библиотеками.
* `input_video.mp4`: временный файл, в который бот скачивает полученное видео.
* `output_video.mp4`: временный файл, в который бот сохраняет обработанное видео.

Лицензия
Этот проект лицензирован под MIT License - подробности смотрите в файле `LICENSE`.

Контакты
Если у вас есть вопросы или предложения пишите на почту указанную в профиле.