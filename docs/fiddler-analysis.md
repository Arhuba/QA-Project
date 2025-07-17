# Анализ запроса GET /get к httpbin.org через Fiddler

## Request Body

- URL: https://httpbin.org/get

- Метод: GET

- Заголовки:

  - User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/138.0.0.0 Safari/537.36

- Sec-ch-ua-platform: "Linux"

  - Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7

  - Host: httpbin.org

## Response Response

- Response code: 200 OK

- Заголовки:

  - Content-Type: application/json

  - Пример тела ответа:

```json

{
  "args": {},
  "headers": {
    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7",

    "Host": "httpbin.org",

    "User-Agent": "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/138.0.0.0 Safari/537.36"
  },

  "url": "https://httpbin.org/get"
}
