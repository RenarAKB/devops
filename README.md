# devops
1.Установить ансибл:

    sudo apt install ansible

2.Выставить в сетевых настройках два адаптера:

    Виртуальный адаптер хоста,
    NAT.

3.Сгенерировать и установить ключ

    ssh-keygen -t rsa cat .ssh/id_rsa > ./ssh/authorized_keys

4.Создать .yml и .html

    mkdir lb touch playbook.yml touch index.html

5.Настроить правила проброса портов Запустить yaml скрипт

    sudo ansible-playbook playbook.yml
