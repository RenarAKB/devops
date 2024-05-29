# devops

### Задание

1)Поднять minikube

2)Создать контейнер

3)Создать тестовый deployment из ngix

### Порядок выполнения работы

Поднятие minikube:

-Включить VT-x/AMD-V .

-Установить Docker и выдать ему права.

     sudo chmod 666 /var/run/docker.sock

-Установить Kubectl
-Создать кластер
      minikube start

![W4JZrjq9j18](https://github.com/RenarAKB/devops/assets/101873862/5653e933-ba47-4ddc-96af-847495733c76)

![9EaSZZHE-Z4](https://github.com/RenarAKB/devops/assets/101873862/70f00c0e-32fc-4560-bdf1-d6c3b886d9d6)

![AU1qWjQwEHc](https://github.com/RenarAKB/devops/assets/101873862/a369e7e2-652c-406c-a6bf-9a36ed05b3a4)


Создание deployment и poda c контейнером (Контейнер базовый тестовый httpd):

     nano kuber-pod.yaml

     kubectl apply -f kuber-pod.yaml

![2](https://github.com/RenarAKB/devops/assets/101873862/3a31d947-0572-416b-89a5-9926b707e08f)

