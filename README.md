
# Второй семинар
20.05.2024S

## Создание веток
git brach branch_name - создает новую ветку

## Слияние веток
git merge branch_name - слияние 2 веток

## Конфликты
конфликты возникают когда затрагивается общее рабочее пространство!
## Удаление веток
git branch -d branch_name
git branch -D branch_name

## Создание репозитория в существующем каталоге
cd C:/Users/Марк/Desktop/Lesson1/

и затем: git init

## Добавление версионного контроля

git add .
git commit -m "комментарий"

## Определение состояния файлов
git status

## Отслеживание изменений
git diff

## Отслеживание лога изменеий
git log --oneline

## Работа с удаленным репозиториями
git remote - просмотр удаленных репозиториев
## Добавить файл в репозиторий
git remote add origin https://github.com/MarkJkeee/FinalLesson.git
git push -u origin main

## Запрос изменений с сервера
git pull origin master