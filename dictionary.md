# **GIT** *commands and description*
___
>## git init
>>*�������� ����������� � ������� ����������*
___
>## git clone <����>
>>*������������ ����������� � ������� ����������* 
___
>## git add <��� ����� ��� (*) ��� �����>
>>_����������� ���� ��� (*) ��� ����� � ����������� ��� ����������� ��������._
___

>### git rm <object or *>
>>_������� ���� ��� (*) ��� ����� �� ����������._
___
>### git status
>>*��������� ����� ����� ���������� *
___
>### git commit
>>*������ "������" �� ������ ������������������ ������ � ��������� �� � ���� ������ Git*

|��������|��������|������|
|:----------:|:----------:|:----------:|
|-a|����������� ��� ��������� � ������|git commit -a|
|-m|��������� �������|git commit -m "���������"|
|--amend|������������ ���������� ������|git commit --amend|
|--author|��������� ������ �������|git commit --amend --author alex\<alex@gmail.com>|
|--date|��������� ���� �������|git commit --amend --date="2023.10.10 10:00"|


___
>### git diff 
>>*���������� ������ � ������� �����������*

|��������|��������|������|
|:----------:|:----------:|:----------:|
|--cached|���������� � ��������� ��������|git diff --cached|
|hash hash|���������� �������|git diff 41d1 1d14|
___

>### git log
*���������� ��� ������� �������� � �� ���-������*

|��������|��������|������|
|:----------:|:----------:|:----------:|
|--stat|���������� ���������� ��������� ������ ��� ������� �������|git log --stat|
|--graph|���������� ����������� ��������� � ������� ASCII|git log --graph|
|--pretty|���������� ������� � �������������� �������,��������� �������� �����: oneline, short, full, fuller � format (� ������� ��������� ����� ������� ���� ������)|$ git log --pretty=format:"%h - %an, %ar : %s"|
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



|��������|��������|������|
|---|-----|------|