# Second seminar. Branches

## Branch creating

* *git checkout branch_name* - команда, осуществляющая переход на ветку *branch_name*

* *git branch* - команда, отбражающая список существующих веток и отмечает в нем текщую;

* *git branch branch_name* - команда, инициализирующая ветку с именем  *branhc_name*

## Branch merging

* *git merge branch_name* - команда, сливающая текущую ветку с веткой *branch_name*

* * git brange -d branch_name* - команда, удаляющая ветку *branch_name*

 Чтобы слить любую ветку с текущей, вызываем git merge  *branch_name*


## Conflicts

данная строка продемострирует конфликтный сценарий при слиянии веток.

Команда git log покажет состояние более новых версий проекта

### Visial

* В Git не принято добавлять файлы изображений, их хранят на сторонних
носителях. 

Чтобы исключить ненужные файлы из загрузки, есть команда git ignore.

* * git log --graph* - команда отображвет коммиты в виде дерева