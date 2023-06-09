# **GIT** *commands and description*
___
>## git init
>>*создание репозитория в текущей директории*
___
>## git clone <путь>
>>*клонирование репозитория в текущую дерикторию* 
___
>## git add <имя файла или (*) все файлы>
>>_индексирует файл или (*) все файлы в репозиторий для последующих коммитов._
___
>### git status
>>*проверяет какие файлы изменились *
___
>### git commit
>>*делает "слепок" на основе проиндексированных данных и добавляет их в базу данных Git*

|параметр|описание|пример|
|----------:|----------:|----------:|
|--author|Подменить автора коммита|git commit -am --author alex\<alex@gmail.com>|
|--date|Подменить дату коммита||
|-a|Закоммитеть все изменения в файлах||
|-m|Сообщение коммита||
|--amend|Перезаписать предыдущий коммит||

___
>### git diff 
>>*сравнивает индекс с рабочей директорией*

|параметр|описание|пример|
|----------:|----------:|----------:|
|--cached|сравниваем с последним коммитом|git diff --cached|
|hash hash|сравниваем коммиты|git diff 41d1 1d14|
___


























>### git rm <object or *>
_индексирует файл или (*) все файлы в репозиторий для последующих коммитов._
___
>### git commit -am "message"
*Combining the commands "git add + git commit "
It is possible if the file has already been added to the repository*
___
>### git log
*displaying the history of all commits with their hash codes*
___
>### git checkout
*moving from one commit to another*
___
>### git checkout master
*return to the current state and continue working*
___

>### git log --graph 
*displaying branches*
___
>### git log --oneline 
*display in one line*
___
>### git branch 
*view all branches*

___
>### git branch <name_branch>
*create a new branch*

___
>### git branch -d
*delete a branch*
___
>### git merge
*merging branches*



|параметр|описание|пример|
|---|-----|------|