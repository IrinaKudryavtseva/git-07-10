# git-07-10


**git init** - Инициализация репозитория

**git status** -  Отобразить статус

**git add file name или первые буквы tab** - добавить file_name версионность

**git reset "file_name"** - убрать версионность

**git add .** - добавить всем файлам в папке версионность

**git reset .** - убрать у всех файлов в папке версионность

**git commit -m "commit_name"** + Зафиксировать изменения в дереве commit_name

**git commit** - фиксирует изменения

**git commit -am "commit_name"** - Позволяет пропустить git add для файлов с состоянием modified

**git checkout "hash_number"** - Сделать перемещение на коммит с hush_number (git checkout master или main вернуться в первоначальное состояние)

**git diff** - показывает изменения файла на данный момент от последнего коммита

**git log** - Показывает историю коммитов

**cd folder_name** - Погрузиться на 1 уровень вложенности в folder_name

**cd ..** - выйти из folder_name на 1 уровень вложенности

**git branch** - просмотреть список существующих веток

**git branch branch_name** - Создать ветку с названием branch_name

**git checkout branch_name** - Переместиться в ветку с названием branch_name

**git branch -d branch_name** - Удалить ветку с названием branch_name (уже смержена)

**git branch -D branch_name** Удалить ветку с названием branch_name (еще не смержена)

**git merge branch_name** - слить ветку branch_name в ветку в кторой мы находимся

**git branch -b branch_name** - Создать ветку и переместиться в нее

**ls** - Отобразить файлы в папке

**mkdir folder_name** - Создать папку folder_name

**new-item file_name** - Создать файл file_name

**git log --graph** - Выводит список коммитов в другом виде

**файл ".gitignore"** - все добавленные документы в этот файл, будут игнорироваться гитом 
**git clone ссылка из gitHub** - добавляет файл из удаленного гита (нужно выйти в папку)

**git push** - отправляет нашу версию репозитория на внешний репозиторий

**git pull** - выкачивает все изменения с gitHub и merge c локальным репозиторием

