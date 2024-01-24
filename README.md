# Домашнее задание к занятию «Базовые объекты K8S» - `Мальцев Виктор`

---
 
Задание 1. Создать Pod с именем hello-world
Создать манифест (yaml-конфигурацию) Pod.
Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
Подключиться локально к Pod с помощью kubectl port-forward и вывести значение (curl или в браузере).

---

Задание 2. Создать Service и подключить его к Pod
Создать Pod с именем netology-web.
Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
Создать Service с именем netology-svc и подключить к netology-web.
Подключиться локально к Service с помощью kubectl port-forward и вывести значение (curl или в браузере).

---

Правила приёма работы
Домашняя работа оформляется в своем Git-репозитории в файле README.md. Выполненное домашнее задание пришлите ссылкой на .md-файл в вашем репозитории.
Файл README.md должен содержать скриншоты вывода команд kubectl get pods, а также скриншот результата подключения.
Репозиторий должен содержать файлы манифестов и ссылки на них в файле README.md.

---

kubectl get pods

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_107.png)

---

скриншот результата подключения

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_105.png)

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_106.png)

---

Ссылка на манифест

https://github.com/vmmaltsev/kuber-homeworks-1.2/blob/main/hello-world.yaml

https://github.com/vmmaltsev/kuber-homeworks-1.2/blob/main/netology-svc.yaml

https://github.com/vmmaltsev/kuber-homeworks-1.2/blob/main/netology-web.yaml