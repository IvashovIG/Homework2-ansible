# Homework2-ansible
Создан каталог Ansible,в нем располагаем Vagrantfile с необходимыми параметрами ВМ.
Запускаем ВМ командой "vagrant up", проверяем доступ по SSH.
С помощью команды "vagrant ssh-config" узнаем параметры подключения к хосту.
Используя данные параметры создаем inventory файл (staging/hosts).
В том же каталоге создадим файл ansible.cfg.
Далее создаем playbook (playbooks/nginx.yml),добавляем шаблон для конфига NGINX (templates/nginx.conf.j2) и модуль, который будет копировать этот шаблон на хост.
Запускаем playbook "ansible-playbook playbooks/nginx.yml" и проверяем его работоспособность.
