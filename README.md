# Генератор Cosmos-кошельков

**`Требуется Python 3.9+`**

1. Клонирование репозитория и переход в папку: `git clone https://github.com/IAmScRay/cosmos_generator && cd cosmos_generator`
2. Создание виртуальной среды: `python3 -m venv venv && source venv/bin/activate`
3. Установка зависимостей: `pip install -r requirements.txt`
4. Запуск: `python3 main.py`

Скрипт уточнит заголовок для генерируемых кошельков (`cosmos` для CosmosHub, `osmo` для Osmosis и т.д.) и их кол-во.
Будет создана по итогу папка `output`, внутри которой будут сохранены все сгенерированные `.xlsx`-файлы Excel.

В таблицах будут получены адреса, приватные ключи и фразы на 24 слова каждого кошелька.
