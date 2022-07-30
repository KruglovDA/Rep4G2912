## Hello!
# Руководство пользователя.
## *Команды git.*
* *git version* - смотрим версию git
* *git config* --global user.name "Liliia" - задаем имя
* *git config* --global user.name "liliia@gmail.com" - задаем email
* создаем папку на ПК GITS1
* *git init* - инициализируем репозиторий в папке
* создаем файл - **manual.md**
* *git add .\manual.md* - добавляем содержимое рабочего каталога в индекс для последующего коммита.
* *git commit -m "Добавили файл"* - сохраняем
* *git status* - текущее состояние гита
* *git log* - посмотреть историю (журнал изменений)
* *git checkout 1942* - переключение между версиями, где 1942 - это первые 4 цифры названия версии
* *git checkout master* - посмотреть версию с последним коммитом
* *git diff* - посмотреть разницу между текущим файлом и сохраненным
* *q* - (quit) возврат в исходное окно терминала
* *git branch* - выводит список веток
* *git branch altbranch* - создать новую ветку с названием altbranch 
* *git checkout altbranch* - перейти в ветку altbranch
* *git merge altbranch* -сливаем две ветки

важно! merge вызывается оттуда, куда хотим залить версию!

* *git branch -d altbranch* - удалить ветку altbranch
* *git commit --amend -m "новое название"* - изменить название последнего коммита
* *git log --graph* - отображает список коммитов в виде дерева
