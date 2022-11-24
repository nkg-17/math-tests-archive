
## Формат задачи
**description.json:**
```json
{
    "title": "",
    "tags": [ "" ],

    "problem": {
        "text": "",
        "answer": ""
    },

    "tips": [ "" ],

    "solution": {
        "text": "",
        "answer": ""
    }
}
```
**Необязательные поля:**
- `tags`
- `problem.answer` - Плейсхолдер в поле ответа
- `solution.answer` - Запятые меняются на точки автоматически


## Структура репозитория
```
root/
    tests/
        <test-ID: int>/
            description.json
            problem-picture.png
        <test-ID: int>/
            description.json
            problem-picture.png
            solution-picture.png
        ...
    README.md
```
- `test-ID` - Неповторяющееся число или строка
