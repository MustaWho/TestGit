# Hello, World!

New string 😒

$ git config --global user.name "MustaWho"
$ git config --global user.email "fiq2000fiq@gmail.com"
$ git config --global core.autorlf true
$ git config --global core.safecrlf warn
$ git config --global core.quotepath off
$ git config --global init.defaultBranch main

$ git config --global --list = просмотр заданных настроек


$ git init = создание логики гит
git status
$ git add README.md = добавление файла
$ git commit -m "Имя измениения" = добавление истории изменения

git log = полное описание истории
git log --oneline = описание в одну строку
git log --oneline --all


git commit --amend "Имя файла" = изменение название созданного комита / при ошибке

git add -A = выбор файла
git commit --amend -m "Имя файла" = добавление файла в созданный комит


git checkout main = переход к основному коммиту последней версии
git checkout код_комита = переход к комиту из истории

get remote -v = проверка привязок
git remote add origin ссылка_с_гита = добавление на сайт гитхаба
