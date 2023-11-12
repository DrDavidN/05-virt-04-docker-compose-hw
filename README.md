# «Оркестрация группой Docker-контейнеров на примере Docker Compose» - Дрибноход Давид

## Задача 1


Создайте собственный образ любой операционной системы (например, debian-11) с помощью Packer версии 1.7.0 . Перед выполнением задания изучите ([инструкцию!!!](https://cloud.yandex.ru/docs/tutorials/infrastructure-management/packer-quickstart)). В инструкции указана минимальная версия 1.5, но нужно использовать 1.7, так как там есть нужный нам функционал


Ответ:

![image](https://github.com/DrDavidN/05-virt-04-docker-compose-hw/assets/128225763/cd92e12b-8ee5-4a8a-aa3e-93b8ef05d905)


## Задача 2

**2.1.** Создайте вашу первую виртуальную машину в YandexCloud с помощью web-интерфейса YandexCloud.        

Ответ:

![image](https://github.com/DrDavidN/05-virt-04-docker-compose-hw/assets/128225763/571556a8-ec2d-44da-92a1-4e0e0f5812d5)


## Задача 3

С помощью Ansible и Docker Compose разверните на виртуальной машине из предыдущего задания систему мониторинга на основе Prometheus/Grafana.
Используйте Ansible-код в директории ([src/ansible](https://github.com/netology-group/virt-homeworks/tree/virt-11/05-virt-04-docker-compose/src/ansible)).

Ответ:

![image](https://github.com/DrDavidN/05-virt-04-docker-compose-hw/assets/128225763/ee43a417-dfbd-4abe-94ec-fd1cfcfe2891)


## Задача 4

1. Откройте веб-браузер, зайдите на страницу http://<внешний_ip_адрес_вашей_ВМ>:3000.
2. Используйте для авторизации логин и пароль из [.env-file](https://github.com/netology-group/virt-homeworks/blob/virt-11/05-virt-04-docker-compose/src/ansible/stack/.env).
3. Изучите доступный интерфейс, найдите в интерфейсе автоматически созданные docker-compose-панели с графиками([dashboards](https://grafana.com/docs/grafana/latest/dashboards/use-dashboards/)).
4. Подождите 5-10 минут, чтобы система мониторинга успела накопить данные.

Ответ:

![image](https://github.com/DrDavidN/05-virt-04-docker-compose-hw/assets/128225763/51ea8cf8-1653-487a-a539-0fdc8adde340)
