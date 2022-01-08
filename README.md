# ✨HRUST WORKFLOW✨

1. Обновляем все пакеты `sudo apt-get update`
2. Устанавливаем __Ansible__ `sudo apt install ansible`
3. Устанавливаем все необходимые пакеты и зависимости следующей командой:
```sh
    $ ansible-playbook [name-of-playbook].yml -K
```
4. Вводим пароль от учетной записи, чтобы Ansible не запрашивал его при каждой итерации.