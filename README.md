# Работа с командной строкой
## Навигация
```
pwd — покажи, в какой я папке;
ls — покажи файлы и папки в текущей папке;
ls -a — покажи также скрытые файлы и папки;
cd first-project  — перейди в папку first-project;
cd first-project/html — перейди в папку html, которая находится в папке first-project;
cd .. — перейди на уровень выше, в родительскую папку;
cd ~ — перейди в домашнюю директорию (/Users/Username);
cd / — перейди в корневую директорию.
```
## **Файлы и папки**
## Создание
```
touch index.html — создай файл index.html в текущей папке;
touch index.html style.css script.js — если нужно создать сразу несколько файлов, можно напечатать их имена в одну строку через пробел;
mkdir second-project — создай папку с именем second-project в текущей папке.
```
## Копирование и перемещение
```
cp file.txt ~/my-dir  — скопируй файл в другое место;
mv file.txt ~/my-dir — перемести файл или папку в другое место.
```
## Чтение
```
cat file.txt  — распечатай содержимое текстового файла file.txt.
```
## Удаление
```
rm about.html — удали файл about.html;
rmdir images — удали папку images;
rm -r second-project — удали папку second-project и всё, что она содержит.
```


# Работа с репозиторием
## Инициализация репозитория
```
git init
```
## Подготовка файла к коммиту

```
git add todo.txt
```
```
git add --all
```
```
git add .
```
## Создание коммита
```
git commit -m "Комментарий к коммиту."
```
## Просмотр информации о коммитах
```
git log
```
## Просмотр состояния файлов
```
git status
```


# Удаленный репозиторий
## Синхронизация локального и удалённого репозиториев
```
git remote add origin https://github.com/YandexPracticum/first-project.git — привяжи локальный репозиторий к удалённому с URL https://github.com/YandexPracticum/first-project.git;
git remote -v — проверь, что репозитории действительно связались;
git push -u origin main — в первый раз загрузи все коммиты из локального репозитория в удалённый с названием origin.
git push — загрузи коммиты в удалённый репозиторий после того, как он был привязан с помощью флага -u.
```
## Клонирование
```
git clone git@github.com:TheGreatOwner/the-great-project.git
```