# Bug Report - JSONPlaceholder DELETE

**ID**: BUG-API-001

**Severity**: Medium

**Endpoint**:  DELETE /posts/1

**Steps**:

    1. Отправить запрос
    2. Получить ответ

**Expected result**: Пришёл код ответа 200 или 204

**Actual result**: Пришёл код ответа 404

**Environment**: JSONPlaceholder production

**Notes**: Ошибка в обработке несуществующего ресурса
