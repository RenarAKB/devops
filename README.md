# devops

Задание:
Создать несколько виртуальных хостов с помощью ansible (на одном сервере несколько сайтов)

Порядок выполнения работы

Создать inventory.ini с ip хоста

Создать плейбук с ролями и сайтами, а так же

Обработчик [handlers] (рестарт nginx)

Темлейты [templates] (html и конфиги)

Таски [tasks] формирование сайтов в цикле

Создать исполняемый shell файл для запуска плейбука с заданными параметрами

     ansible-playbook ./playbook.yml -i ./conf.ini --diff --ask-become-pass

Запустить его и проверить

    sh playbook.sh

    curl http://192.168.1.18 -H 'Host: first.com'

Результат - ![result](https://github.com/RenarAKB/devops/assets/101873862/adbd9620-47d7-486a-aa28-37fd808c9ca8)

