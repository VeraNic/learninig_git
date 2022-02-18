# **GIT COMMANDS**

![git](https://cdn-images-1.medium.com/fit/t/1600/480/1*BCZkmZR1_YzDZy22Vn4uUw.png)

## Настройки git

>* **git version** - вывести версию программы git
>
>* **git config --global user.name « *<FirstName.LastName>* »** - сообщить программе своё имя
>
>* **git config --global user.email *<your_mail@example.com>*** - сообщить программе свой e-mail
>
>* **git config --global user.name** - вывести на экран сохранённое в программе имя пользователя
>
>* **git config --global user.email** - вывести на экран сохранённый в программе e-mail пользователя

## Смена редактора

>* **git config --global core.editor "code --wait"** - VS Code
>
>* **git config --global core.editor "nano -w"** - Nano
>
>* **git config --global core.editor "'c:/program files/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"** - Notepade++
>
>* **git config --global core.editor "vim"** - Vim

## Начало работы с репозиториями

>* **git init** - создать репозиторий в папке для отслеживания изменений файлов
>
>* **git status** - узнать, какие изменения произошли
>
>* **git add  *<file.name>*** - индексация измененного файла, либо оповещение о
создании нового (после ввода первых двух символов имени отредактированного файла можно нажать TAB)
>
>* **git add .** - внести в индекс все изменения, включая новые файлы
>
>* **git commit -m " *< message>* "** - зафиксировать изменения, сопроводив их комментарием
>
>* **git log** - просмотр журнала изменений
>
>* **git checkout <????>** - переход к версии, коммит которой начинается с указанных в команде четырех (или более) символов
>
>* **git checkout master** - возврат к актуальной версии файла
>
>* **git diff** - показ разницы между текущим состоянием файла и сохраненным
>
