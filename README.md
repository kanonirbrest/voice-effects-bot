# Voice Effects Telegram Bot

Бот для наложения эффектов на голосовые сообщения в Telegram.

## Установка

1. Клонируйте репозиторий
2. Установите зависимости:
```bash
pip install -r requirements.txt
```
3. Создайте бота через @BotFather и получите токен
4. Вставьте токен в файл .env:
```
TELEGRAM_TOKEN=your_bot_token_here
```

## Запуск

```bash
python bot.py
```

## Использование

1. Запишите голосовое сообщение
2. Вызовите бота через @имя_бота
3. Выберите эффект из предложенных
4. Бот обработает сообщение и вернет результат

## Доступные эффекты

- Робот
- Эхо
- Замедление
- Ускорение
- Обратное воспроизведение 