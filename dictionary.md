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

>### git rm <object or *>
>>_удаляет файл или (*) все файлы из репоитория._
___
>### git status
>>*проверяет какие файлы изменились *
___
>### git commit
>>*делает "слепок" на основе проиндексированных данных и добавляет их в базу данных Git*

|параметр|описание|пример|
|:----------:|:----------:|:----------:|
|-a|Закоммитеть все изменения в файлах|git commit -a|
|-m|Сообщение коммита|git commit -m "Сообщение"|
|--amend|Перезаписать предыдущий коммит|git commit --amend|
|--author|Подменить автора коммита|git commit --amend --author alex\<alex@gmail.com>|
|--date|Подменить дату коммита|git commit --amend --date="2023.10.10 10:00"|


___
>### git diff 
>>*сравнивает индекс с рабочей директорией*

|параметр|описание|пример|
|:----------:|:----------:|:----------:|
|--cached|сравниваем с последним коммитом|git diff --cached|
|hash hash|сравниваем коммиты|git diff 41d1 1d14|
___

>### git log
*отображает всю историю коммитов с их хэш-кодами*

|параметр|описание|пример|
|:----------:|:----------:|:----------:|
|--stat|показывает статистику изменённых файлов для каждого коммита|git log --stat|
|--graph|визуальное отображение ветвлений в формате ASCII|git log --graph|
|--pretty|показывает коммиты в альтернативном формате,возможные варианты опций: oneline, short, full, fuller и format (с помощью последней можно указать свой формат)|$ git log --pretty=format:"%h - %an, %ar : %s"|
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