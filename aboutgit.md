# Git - Это
 *__Git__ - это система контроля версий. Помогает работать в команде*

# Подготовка репозитория

## Настройка имени и почты

* **git config user_name**
* **git config user email**

## настройка локального репезитория

* **git init**


# Создание сохранений

## Добавитть файл к коммиту

* **git add file_name**

## Добавление всех файлов к коммиту

* **git add .**
## Зафиксировать изменения

* **git commit -m "some info"**
## Добавить все файлы к коммиту

* **git commit -a -m "some info"**


# Проверка состояния репозитория

## Команды
* **git status**

Выводит информацию о состоянии репозитория

* **git diff** 

Показывает разницу между текущими изменениями и теми что закомичены

* **git show branch code**

Показывает какие изменения были в коммите c конкретным номером(смотри номер в git log)


# Перемещение между сохранениями

# Журнал изменений

* **git log**

# Ветки в git
*Показывает все ветки*

* git branch

*Создать ветку*

* git branch branch_name

*Переход между ветками*

* git checkout branch_name
# Слияние веток и решение конфликтов

* git merge branch_name

Добавляет информацию из ветки branch_name в текущую

*Конфликт веток решается с помощью ручного изменения файла и коммита с этими изменениями*

# Удаление веток
 * git branch -d branch_name


# Справка

**--help**
* git log --help
* git commit --help

# **Работа с удаленными репозиториями**

## Зарегестрироваться например на  **GITHUB.com**

# Добавить репозиторий себе

1. Зайти на страницу с нужным репозиторием

2. Нажать кнопку "Code" и копировать ссылку на репозиторий

3. В терминале ввести команду  **git clone ссылка**
и скопировать репозиторий себе

3. С помощью команды **cd** войти в скачанный репозиторий

# Загрузить репозиторий на сайт

1. Зайти в свой профиль на Github

2. Нажать кнопку **New** и 
ввести название репозитория

3. Следовать инструнции подсказанной Github

**Команды**

* git remote add origin ссылна на реп

* git branch -M main

* git push -u origin main

* git push - отправить изменения на удаленный реп 

* git pull - скачать из удаленного реп

# Изменить ссылку на перозиторий

git remote set-url origin новая ссылка на реп

# Предложить свой репозиторий другому

1. Зайти на страницу репозитория user_name

2. Нажать кнопку кнопку **Fork**

3. Вернуться в свой аккаунт

4. Клонировать скопированный репозиторий себе

5. внести изменения в терминале и сохранить обратно на Github




