+7-999-888-77-66
# Инструкция по связке Git - GitHub

Чтобы склонировать репозиторий к себе на ПК, используется команда: 
> **git clone URL** - клонируется репозиторий по адресу **URL** 
Привет, Гитхаб
Привет от Алексея!

# Инструкция по работе с Git

> **git init** - создание пустого репозитория в выбранной папке.

> **git add file_name** – добавить файл или файлы к следующему коммиту

> **git add .** - сохранить все файлы, которые были добавлены в наш репозиторий. Добавили **30** картинок - "gid add ." сохранит все **30** файлов сразу

> **git status** – получить информацию от git о его текущем состоянии

> **git commit -m “message”** – создание коммита с сообщением(заметкой)

> **git log** – вывод на экран истории всех коммитов с их хеш-кодами

> **git branch** – посмотреть список веток в репозитории

> **git branch <branch_name>** – создать новую ветку

> **git checkout <branch_name>** – переход к другой ветке

> **git branch -d <branch_name>** – удалить ветку

> **git log --graph** – журнал коммитов с визуализацией

> **git commit -am “текст_коммита”** – создание изменения и его коммит

> **git checkout -b branch_name** – создание ветки и переход в нее

> **git checkout "id"** – переход от одного коммита к другом

> **git checkout master** – вернуться к актуальному состоянию и продолжить работу

> **git diff** – увидеть разницу между текущим файлом и закоммиченным файлом

>**git clone** <url-адрес репозитория> – клонирование внешнего репозитория на локальный ПК

>**git pull** – получение изменений и слияние с локальной версией

>**git push** – отправляет локальную версию репозитория на внешний

## Выделение текста
Чтобы выделить текст курсивом необходимо обрамить его звездочками (*) или знаком нижнего подчеркивания (_). Например, *вот так*, или _вот так_

Чтобы выделить текст полужирным необходимо обрамить его двойными звездочками (**) или двойным знаком нижнего подчеркивания (__).
Например, **вот так**. или __вот так__.

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например, _текст может быть выделен курсивом и при этом быть **полужирным**_.

Чтобы выделить текст полужирным курсивом необходимо обрамить его тройными звездочками (***) или тройным знаком нижнего подчеркивания (__).
Например, ***вот так***. или ___вот так___.

Чтобы зачеркнуть текст необходимо обрамить его двойными тильдами (~~).
Например, ~~вот так~~.

## Списки

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*) или знаком +. Например, вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки необходимо пункты выделить просто пронумеровать.
Например, вот так:
1. Элемент 1
2. Элемент 2