# B6-skillfactory-ansible-main

1. Создать 3 ВМ в Я.Облаке (минимальная конфигурация: 2vCPU, 2GB RAM, 20 GB HDD): vm1 и vm2 (Ubuntu 20.04), vm3 (Centos 8).
2. Установить на vm1 Ansible.
3. Создать на vm1 пользователя для Ansible.
4. Настроить авторизацию по ключу для этого пользователя с vm1 на vm2 и vm3.
5. Добавить в inventory информацию о созданных машинах. vm2 и vm3 должны быть в группе app, vm1 — в группе database и web.
6. Написать плейбук, реализующий следующее:
- на машинах группы app выполняется установка и запуск Docker;
- на машинах группы database выполняется установка и запуск postgresql-server (версия и data-директория должны быть переменными, задающимися в inventory).
7. Протестировать написанный плейбук.
8. Выложить плейбук и inventory в GitHub. Создайте отдельный репозиторий Ansible.
9. Прислать ментору ссылку на репозиторий с плейбуком.
