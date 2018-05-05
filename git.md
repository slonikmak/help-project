# Справка по GIT

## Создание репозитория

git init

## Добавление файла

git add file.name

## Добавить все файлы

git add -A

## Коммит (фиксация изменений)

git commit -m "commit name"

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
