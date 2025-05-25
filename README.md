# Monero Mining Telegram Bot 🤖⛏️

Бот для мониторинга майнинга Monero (XMR) через Telegram.  
Отслеживает баланс, хэшрейт, воркеров и выплаты с пула MoneroOcean.

## Возможности
- 📊 **Статистика майнинга**: баланс, хэшрейт, шары
- 🖥 **Мониторинг воркеров**: хэшрейт каждого worker
- 💸 **История выплат**: последние транзакции
- 🔄 **Автообновление**: кнопки для быстрого обновления данных
- 📅 **Ежедневные отчеты**: автоматически в 21:00

## Как использовать
1. Добавьте бота: [@checkmyxmr_bot](https://t.me/checkmyxmr_bot)
2. Команды:
   - `/start` – меню бота
   - `/stats` – текущая статистика
   - `/workers` – список воркеров
   - `/payments` – история выплат

## Установка
1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/ваш-логин/monero-mining-bot.git
   cd monero-mining-bot
2. Установите зависимости:

bash
pip install python-telegram-bot requests
Запустите бота:

bash
python bot.py
Конфигурация
Задайте переменные в config.py или через окружение:

WALLET_ADDRESS: Ваш XMR-кошелек

TELEGRAM_BOT_TOKEN: Токен бота от @BotFather

TELEGRAM_CHAT_ID: Ваш chat_id для отчетов
