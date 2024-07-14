# ЭТО ФАЙЛ С ОСНОВНЫМИ GIT КОМАНДАМИ
This file was compiled and uploaded to GIT by George Borisovsky.




## команды управления GIT
------

+ pwd # print working directory — «показать рабочую папку
+ cd # change directory — «сменить директорию
+ ~ # домашняя дирректория
+ ls # list directory contents отобразить содержимое директории»
+ cd .. # вернуться на уровень выше
+ -a # скрытые файлы
+ touch # создать файл
+ mkdir # создать директорию
+ cp # копирование фалов
+ mv # move — «переместить
+ cat # concatenate and print
+ rm # remove — «удалить»
+ rmdir # emove directory — «удалить директорию
+ rm -r # удалить вместе со всем её содержимым
+ && - mkdir second-project && cd second-project && touch index.html style.css
+ Tab # автозаполнение 
+ cd c:/ # диск ц

## команды подключения GIT ##
+ git config --global user.name "" # «конфигурация», «настройка
+ git config --global user.email # добавить маил
+ cat ~/.gitconfig  # настройки
+ git init # Сделать папку репозиторием
+ rm -rf .git # разгитить папку
+ git status # состояние репозитория
+ git add # Подготовить файлы к сохранению
+ git add --all # все файлы
+ git add . # добавить всю текущую папку
+ git commit # сделать комит
+ git commit -m 'Мой первый коммит!' 
+ git log # просмотр коммитов
+ $ ssh-keygen -t ed25519 -C "электронная почта, к которой привязан ваш аккаунт на GitHub"
+ ls -a ~/.ssh # проверка shh
+ git remote add # Привязать удалённый репозиторий к локальному
+ origin # можно обращаться к главному удалённому репозиторию
+ shift + Insert # вставить копированный текст или правый клик Paste
+ git remote -v # Убедиться, что репозитории связаны
+ -v # короткая форма флага --verbose (англ. «подробный»). Он позволяет показать больше информации в выводе.
+ git push origin master # Отправить изменения на удалённый репозиторий
+ git push -u origin master gi# первый пуш
+ git clone # клонирование репозитория

## ОБРАБОТКА ОШИБОК / ОШИБКИ / ERRORS ##
---------
+ fatal: Unable to create '/path/my_proj/.git/index.lock': File exists.
 rm -f ./.git/index.lock
Если ввести git commit без флага -m, откроется редактор Vim. Чтобы выйти из него, нажмите клавишу Esc, наберите последовательность символов :q! и нажмите Enter.



