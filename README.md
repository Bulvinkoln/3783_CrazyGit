# Описание нашего маленького проектика
## Срок реализации проекта до 01.01.2023

#### 3783_CrazyGit

# Инструкция для работы с Git и удалёнными репозиториями
## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

## Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"

#### Информация по командам git push & git pull
git push - отправляет всю информацию на Github
git pull - забирает информацию с Github

Добавив текст необходимо сохранить информацию сочитанием клавиш Ctrl+S
Далее прописываем команды: git add (TAB) ---> git commit -m "Текст что сделано" ---> направляем всю информацию на Github командой git push

Добавив текст на Github (через значок карандаша), добавляем комментарий в поле ниже, сохраняем информацию нажав кнопку "Commit changes"
Зайдя в VS Code необходимо прописать команду git pull, и вся информация отобразится.

Для того чтобы скорректировать проект другого человека необходимо:
1. Делаем форк (fork) на Github;
2. Мы делаем git clone для нашей версии этого репозитория;
3. Создаем ветку с предлагаемыми изменениями (git branch имя ветки, перевод на эту ветку git checkout имя ветки)
4. Производим все изменения только в этой ветке;
5. Отправляем эти изменения на свой аккаунт командой git push;
6. На сайте Guthub появляется возможность отправить pull request.