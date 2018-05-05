# Справка по GIT. Основные команды

## Создание репозитория

```bash
git init
```

## Добавление файла

```bash
git add file.name
```

## Добавить все файлы

```bash
git add -A
```

## Коммит (фиксация изменений)

```bash
git commit -m "commit name"
```

## Коммит(В первой строке введите комментарий. Сохраните файл и выйдите из редактора (для этого в редакторе по-умолчанию (Vim) вам нужно нажать клавишу ESC, ввести :wq и нажать Enter). )

```bash
git commit -a
```

## Подключение к удалённому репозиторию

```bash
git remote add origin https://github.com/slonikmak/help-project.git
```

## Отправка изменений на сервер

```bash
git push origin master
```

## Клонирование репозитория

```bash
git clone https://github.com/repo.git
```

## Запрос изменений с сервера

```bash
git pull orign master
```

## Создание новой ветки (Это создаст новую ветку, точную копию ветки master.)

```bash
git branch amazing_new_feature
```

## Переключение между ветками

```bash
git checkout amazing_new_feature
```

## Создание ветки от ветки Develop и переключение на неё

```bash
git checkout -b myfeature develop
```

## Список веток

```bash
git branch
```

## Слияние веток

```bash
git merge branch.name
```

## Создание ветки develop на сервере и загрузка файлов

```bash
git push --set-upstream origin develop
```

## Удаление ветки

```bash
git branch -d branch.name
```

## Список изменений

```bash
git log
```

## Изменение предыдущего комита

```bash
git commit --amend -m "commit name"
```