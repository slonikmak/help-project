# Справка по GIT. Основные команды

## Создание репозитория

git init

## Добавление файла

git add file.name

## Добавить все файлы

git add -A

## Коммит (фиксация изменений)

git commit -m "commit name"

## Коммит незафиксированных изменений

git commit -a "commit name"

## Подключение к удалённому репозиторию

git remote add origin https://github.com/slonikmak/help-project.git

## Отправка изменений на сервер

git push origin master

## Клонирование репозитория

git clone https://github.com/repo.git

## Запрос изменений с сервера

git pull orign master

## Создание новой ветки (Это создаст новую ветку, точную копию ветки master.)

git branch amazing_new_feature

## Переключение между ветками

git checkout amazing_new_feature

## Список веток

git branch

## Слияние веток

git merge branch.name

## Создание ветки develop на сервере и загрузка файлов

git push --set-upstream origin develop

## Удаление ветки

git branch -d branch.name