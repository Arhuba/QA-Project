# Анализ POST-запроса к httpbin.org через Fiddler

# Цель: 
Перехватить и проанализировать POST-запрос, отправленный на https://httpbin.org/post.

# ⚙️ Инструменты

- Postman
- Fiddler Everywhere
- Linux Mint 21

# 📤 Запрос

- **Метод:** POST
- **URL:** `https://httpbin.org/post`
- **Тело запроса:** 
```json
{
  "name": "Artyom",
  "role": "QA"
}
