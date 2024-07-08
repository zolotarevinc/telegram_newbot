# Начинающий Телеграм бот

Этот проект представляет собой простого Телеграм бота, написанного на Python с использованием библиотеки `python-telegram-bot`. Бот отвечает на команды `/start` и `/help`, а также на любые текстовые сообщения.

## Установка

1. Склонируйте репозиторий:
    ```bash
    git clone https://github.com/ваш_пользователь/telegram-bot.git
    cd telegram-bot
    ```

2. Создайте виртуальное окружение и активируйте его:
    ```bash
    python -m venv venv
    source venv/bin/activate  # Для Windows: venv\Scripts\activate
    ```

3. Установите необходимые зависимости:
    ```bash
    pip install -r requirements.txt
    ```

4. Создайте файл `.env` и добавьте ваш Телеграм токен:
    ```env
    TOKEN=ваш_токен_здесь
    ```

## Использование

Для запуска бота выполните команду:
```bash
python bot.py
