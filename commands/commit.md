## git commit

``git commit`` - совершение коммита

Коммиты - базовое понятие во всех системах контроля версий, поэтому совершаться
он должен легко и по возможности быстро. В самом своем простом виде достаточно
после индексации набрать:

``git commit``

Есть несколько ключей, упрощающих работу с ``git commit``:

```
git commit -a - совершит коммит, автоматически индексируя изменения в файлах
проекта. Новые файлы при этом индексироваться не будут! Удаление же файлов
будет учтено.
```
```
git commit -m "комментарий" - комментируем коммит прямо из командной строки
вместо текстового редактора.
```
```
git commit [файл] - внесет в индекс и создаст коммит на основе изменений
единственного файла.
```

[На главную](./../readme.md)