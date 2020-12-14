# LR6
Лабораторная работа №6

***

## Отчёт

### Шаги 1-6

После установки Git следует его настройка:

![1](screens/config.PNG)

Далее клонируем удёлённый репозиторий:

![2](screens/clone.PNG)

Добавляем файл через интерфейс github:

![3](screens/github_file.PNG)

Подтягиваем изменения в локальный репозиторий:

![4](screens/pull.PNG)

### Шаги 7-13

Получаем историю операций для каждой ветки:

master

![5](screens/master_log.PNG)

branch1

![6](screens/branch1_log.PNG)

Последние изменения:

![7](screens/last_changes.PNG)

#### Слияние ветки branch1 в master и разрешение конфликта с помощью mergetool.

Копируем branch1 из удалённого репозитория:

![8](screens/clone_branch1.PNG)

Возвращаемся на мастер:

![9](screens/back_to_master.PNG)

Пытаемся сделать merge, но сталкиваемся с конфликтом:

![10](screens/conflict.PNG)

Поэтому запускаем mergetool:

![11](screens/mergetool_cmd.PNG)

![12](screens/mergetool.PNG)

Закрываем mergetool и после успешного слияния удаляем локальную branch1

![13](screens/delete_branch1.PNG)

После этого делаем первый commit:

![14](screens/1st_commit.PNG)

Далее сделаем дополнительный commit, чтобы его откатить.<br/>
Для этого изменим github_file, который был добавлен через github:

![15](screens/status_after_changes.PNG)

![16](screens/add_file.PNG)

Делаем commit:

![17](screens/commit_to_be_deleted.PNG)

Далее используем reset, чтобы его откатить:

![18](screens/hard_reset.PNG)

И создаём ветку для отчёта:

![19](screens/report_branch.PNG)




