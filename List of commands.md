# Основные команды утилиты "Git"

* **git init** - *initialization* - инициализация локального репозитория

* **git help** - справка по всем командам

* **git help <название_команды>** - справка по выбранной команде

* **git status** - получение информации о текущем состоянии файла

* **git add <название_файла>** - добавление нововнесённых данных к следующему commit

* **git commit -m "message"** - создание commit в текущей ветви с комментарием

* **git commit -am "message"** - команда создания commit в текущей ветви с ключами -a (add), -m (message) и комментарием

* **git log** - вывод на экран терминала списка commit текущей ветви с их историями и хеш-кодами

* **git log --graph** - вывод на экран терминала списка commit текущей ветви в виде графа/дерева

* **git log --oneline** - вывод на экран терминала списка commit текущей ветви без строк авторства и времени создания

* **git log --graph --oneline** -  вывод на экран терминала списка commit текущей ветви в виде графа/дерева без строк авторства и времени создания

* **git reflog** - вывод на экран терминала истории действий с HEAD

* **git checkout <хэш_код_commit>** - переход к указанному commit

* **git checkout <название_ветви>** - переход к указанной ветви

* **git checkout master** - переход к основной ветви файла

* **git checkout -b <название_ветви>** - создание новой ветви и переход к ней

* **git checkout <название_ветви>^** - переход назад по списку commits от текущего commit на указанное количество операторов (^) или ~<num>

* **git checkout HEAD^** - перенос HEAD к предыдущему значению на указанное количество операторов (^) или ~<num>

* **git branch** - просмотр списка ветвей и текущего местонахождения в них

* **git branch <название_ветви>** - создание новой ветви без перехода к ней

* **git branch -d <название_ветви>** - удаление указанной ветви

* **git branch -f <название_ветви> HEAD~3** - принудительное прикрепление указанной ветви на три, например, значения HEAD назад

* **git clone <адрес_репозитория>** - создание локальной копии репозитория с онлайн-сервера на текущий компьютер

* **cd <название_папки>** - смена местоположения/дериктории на указанную папку

* **git remote add origin <веб-адрес репозитория>** - связывание текущего локального репозитория с указанным веб-репозиторием

* **git branch -M <название_ветви>** - обозначение основной ветви

* **git push -u origin master/main** - отправка файлов с текущего репозитория на веб-репозиторий

* **git push** - выгрузка нововнесённых данных с текущего репозитория в привязанный веб-репозиторий

* **git pull** - загрузка актуальных данных с привязанного веб-репозитория в текущий локальный

* **git pull request** - выгрузка данных с текущего репозитория в чужой веб-репозиторияй

* **git diff <исходная_ветвь> <целевая_ветвь>** - просмотр изменений относительно двух ветвей

* **git merge <название_ветви>** - копирование всех данных из указанной ветви в текущую ветвь

* **git remote rm origin** - удаление связи текущего репозитория с удалённым
