По всем вопросам писать [сюда](https://t.me/xfnty).

## Структура репозитория
```
tests/
    <ID>/
        (текст условия) 
        problem.md

        (текст решения) 
        solution.md

        (картинка для предпросмотра) 
        preview.(png, jpg, svg, webp, ...)

        (Другие изображения, на которые ссылаются problem.md и solution.md)
    <ID>/
        problem.md
        solution.md
        preview.png
    ...
README.md
```
- `ID` - Неповторяющийся номер теста (строка или число).

## Формат файлов `problem.md` и `solution.md`
Тексты условия и решения имеют формат 
простого [Markdown](https://guides.hexlet.io/ru/markdown/) документа.

> **Note**  
> Все ссылки на изображения должны 
> находиться в одной папке с текстом задачи и
> содержать лишь имя файла, например `![](preview.svg)`.
