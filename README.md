# devops

Задание: Создать плейбук для сканирования запрошенных серверов при помощи nmap

Порядок выполнения работы
     sudo apt install nmap

Создать invntory.ini с id и паролем (сменил виртуалку, ssh по паролю)

     touch inventory.ini cat >> inventory.ini

Создать плейбук

     touch pb_nmap.yml

Создать файл со сканируемыми серверами

     touch targets.txt
 
Выполнить плейбук

      ansible-playbook pb_nmap.yml -i inventory.ini --diff

Результат представлен ниже 
![1](https://github.com/RenarAKB/devops/assets/101873862/901e24bf-fa40-4b32-a6ff-a940b79c62aa)

