# LR6
Лабораторная работа №6

Настраивается клиент git, вводится имя и email с помощью команд git config --global user.name <username> и git config --global user.email <email>

![Image alt](https://github.com/MakDarya/LR6/raw/reportMaklashova/images/image1.jpg)

Затем клонируем удаленный репозиторий на свой компьютер командой git clone <url>

![Image alt](https://github.com/MakDarya/LR6/raw/reportMaklashova/images/image2.jpg)

Командой cd LR6/ добавляем файл

![Image alt](https://github.com/MakDarya/LR6/raw/reportMaklashova/images/image3.jpg)

Подтягиваем изменения в локальный репозиторий командой git pull

![Image alt](https://github.com/MakDarya/LR6/raw/reportMaklashova/images/image4.jpg)

Командой git log просмотрим коммиты ветки master

![Image alt](https://github.com/MakDarya/LR6/raw/reportMaklashova/images/image5.jpg)

Просмотрим ветки в текущем репозитории с помощью команды git branch, а командой git checkout branch1 перейдем в ветку branch1

![Image alt](https://github.com/MakDarya/LR6/raw/reportMaklashova/images/image6.jpg)

Взглянем на коммиты ветки branch1 командой git log

![Image alt](https://github.com/MakDarya/LR6/raw/reportMaklashova/images/image7.jpg)

Для подробного рассмотрения воспользуемся командой git log -p

![Image alt](https://github.com/MakDarya/LR6/raw/reportMaklashova/images/image8.jpg)

Слияние в ветку master выполняем командой git merge branch1
Возникает конфликт, причина которого в том, что файл был изменен, а коммит был не добавлен. Используем команду git status, чтобы это проверить, а git add и git commit, чтобы исправить.

После слияния удаляем ветку branch1 командой git branch -d branch1

![Image alt](https://github.com/MakDarya/LR6/raw/reportMaklashova/images/image9.jpg)

![Image alt](https://github.com/MakDarya/LR6/raw/reportMaklashova/images/image10.jpg)

![Image alt](https://github.com/MakDarya/LR6/raw/reportMaklashova/images/image11.jpg)

Создаем изменения и фиксируем их с помощью команды git add, а также коммитим командой git commit

![Image alt](https://github.com/MakDarya/LR6/raw/reportMaklashova/images/image12.jpg)

![Image alt](https://github.com/MakDarya/LR6/raw/reportMaklashova/images/image13.jpg)

Производим хард откат коммита командой git reset --hard HEAD~1

![Image alt](https://github.com/MakDarya/LR6/raw/reportMaklashova/images/image14.jpg)

Создаем ветку для отчета и сразу переходим к ней командой git checkout -b report

![Image alt](https://github.com/MakDarya/LR6/raw/reportMaklashova/images/image15.jpg)

Оформляем отчёт в файле README.md
С помощью git log просматриваем итоговую историю операций

![Image alt](https://github.com/MakDarya/LR6/raw/reportMaklashova/images/image16.jpg)

![Image alt](https://github.com/MakDarya/LR6/raw/reportMaklashova/images/image17.jpg)

После создания отчета сохраняем его командой git add и коммитим.
Все локальные изменения отправляем в сетевое хранилище GitHub командой git push