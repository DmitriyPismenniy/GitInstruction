# Installation instruction and common commands for Git 

## Installation of Git & Visual Studio Code

Установка Git для Windows, MAC, Linux: https://git-scm.com/downloads

Установка VSCode для Windows, MAC, Linux: https://code.visualstudio.com/Download

При первом использовании Git необходимо представиться.  Для этого нужно ввести в терминале 2 команды:

git config --global user.name «Ваше имя английскими буквами»  

git config --global user.email ваша почта@example.com

Проверить версию Git можно с помощью команды: git --version

## Common commands for Git

* **git init** – инициализация локального репозитория
* **git status** – получить информацию от git о его текущем состоянии
* **git add** – добавить файл или файлы к следующему коммиту
* **git commit -m “message”** – создание коммита
* **git log** – вывод на экран истории всех коммитов с их хеш-кодами
* **git checkout** – переход от одного коммита к другому
* **git checkout master** – вернуться к актуальному состоянию и продолжить работу
* **git diff** – увидеть разницу между текущим файлом и закоммиченным файлом

## Branch commands for Git
* **git branch** - вывод списка веток
* **git branch new_branch_name** - создание ветки с именем new_branch_name
* **git checkout new_branch_name** – переход на ветку с именем new_branch_name
* **git merge existing_branch_name** - объединение текущей ветки с веткой existing_branch_name


