По всем вопросам писать [сюда](https://t.me/xfnty).

## Структура репозитория
```
tests/
    <ID>/
        (текст условия) 
        problem.md

        (текст решения) 
        solution.md

        (картинка для предпросмотра, без расширения файла) 
        preview

        (Другие изображения, на которые ссылаются problem.md и solution.md)
    <ID>/
        problem.md
        solution.md
        preview
    ...
README.md
```
- `ID` - Неповторяющийся номер теста (строка или число).

## Формат файлов `problem.md` и `solution.md`
Тексты условия и решения имеют формат 
простого [Markdown](https://guides.hexlet.io/ru/markdown/) документа.

> **NOTE**  
> Все ссылки на изображения после обработки будут начинаться с 
> `https://raw.githubusercontent.com/nkg-17/math-tests-archive/main/tests/<ID>/`.
> Из за этого можно просто писать `![](preview)`, не задумываясь о полном URL 
> файла.
> 
> Так, например, ссылка на `preview.jpg` теста `1` будет выглядеть так: 
> `https://raw.githubusercontent.com/nkg-17/math-tests-archive/main/tests/1/preview`. 
> 
> Поэтому все изображения, на которые есть ссылки в тексте задачи, должны быть
> скопированы в папку теста (`tests/<ID теста>`).
