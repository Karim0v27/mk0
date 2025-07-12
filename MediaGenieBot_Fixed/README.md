# MediaGenieBot

🎧 Телеграм-бот для поиска и загрузки музыки, фильмов и аниме.

## Функции

- `/music <название>` — поиск и загрузка музыки с YouTube в mp3
- `/movie <название>` — поиск информации о фильме с IMDb
- `/anime <название>` — поиск информации об аниме с MyAnimeList

## Развёртывание на Render

1. Залей репозиторий в GitHub.
2. Подключи его на [https://render.com](https://render.com).
3. Укажи переменные окружения:
   - `BOT_TOKEN` — токен Telegram-бота
   - `WEBHOOK_HOST` — например, `https://yourapp.onrender.com`
4. Build command:
   ```bash
   pip install -r requirements.txt
   ```
5. Start command:
   ```bash
   python main.py
   ```

---

🔥 Сделано с ❤️ для Telegram