# My git instruction 

* __"git init"__ - *команда, инициализирующая репозиторий в текущей папке*;

* __"git status"__ - *команда, отображающая текущее состояние репозитория*;

* __"git version"__ - *команда, показывающая текущую версию git*;

* __"git add file_name"__ - *команда, добавляющая файлы, как отслеживаемые. __"file_name"__ - это название файла, который нужно добавить. Можно вывести нажатием клавиши __"tab"__ после команды __"git add"__*.

* __"git commit -m "comment""__ - *команда, сохраняющая текущее состояние. __"comment"__ - это комментарий к данному коммиту. Например, __git commit -m "Info added"__*;

* __"git log"__ - *команда, позволяющая вывести список всех коммитов*;

* __"git checkout commit_name"__ - *команда, позволяющая переходить между разными коммитами. __"commit_name"__ - это название коммита (можно использовать первые четыре символа). Например, __git checkout abcd__*;

* __"git diff"__ - *команда, показывающая разницу между текущим состоянием файла и сохраненным. (__Красным__ цветом указываются удаленные строки. __Зеленым__ цветом указываются добавленные строки)*;

* __"git commit --amend -m "comment""__ - *команда, позволяющая редактировать описание коммита. Необходимо изменить название __"comment"__. Например, __git commit --amend -m "comment1"__*

* __"git checkout master"__ - *команда, позволяющая перейти на ветку __master__*;

* __"git config --global user.name "name""__ - *команда, позволяющая ввести имя пользователя. __"name"__ - __"Имя пользователя"__. Например, __git config --global user.name "Ivan"__*;

* __"git config --global user.email "email""__ - *команда, позволяющая ввести email пользователя. __"email"__ - __"email пользователя"__. Например, __git config --global user.email "ivan@gmail.com"__*;

* __"git branch branch_name"__ - *команда, позволяющая добавить новую ветку. __branch_name__ - это название ветки. Например, __git branch tutor__*;

* __"git branch"__ - *команда, показывающая все ветки и какая из веток активная*;

* __"git checkout branch_name"__ - *команда, позволяющая перейти на определенную ветку. __branch_name__ - это название ветки. Например, __git checkout tutor__*;

* __"git merge branch_name"__ - *команда, позволяющая добавить информацию из другой ветки в активную. __branch_name__ - название ветки. Например, __git merge image__*;

* __"git branch -d branch_name"__ - *команда, позволяющая удалить определенную ветку. __branch_name__ - это название ветки. Например, __git branch -d image__*;

* __"git log --graph"__ - *команда, позволяющая вывести список коммитов альтернативным способом*;

* __"git clone adress"__ - *команда, позволяющая git скопировать репозиторий из github. __Adress__ - адрес репозитория с github. Например, git clone https://github.com/ShafigullinIK/group_903.git*;

* __"git push"__ - *команда, отправляющая то, что есть в локальном репозитории в github. (При первой привязке нужно авторизоваться);*
 
* __"git pull"__ - *команда, позволяющая перенести изменения из github в программу git*;

* __"git branch -M branch_name"__ - *команда, позволяющая указать главную ветку. __Branch_name__ - это название ветки. Например, __git branch -M master__;*

* __git checkout -b branch_name__ - *команда, позволяющая создать новую ветку и сразу же перейти на нее. __Branch_name__ - это название ветки. Например, __git checkout -b main__;*
