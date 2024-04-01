## Плейбук для установки прокси Marzban

Запуск:
```bash
ansible-playbook -i inventory playbook.yml
```

В плейбук можно внести изменения (вынесены в переменные):
| Variable                          | Description                                                                                           |
| --------------------------------- | ----------------------------------------------------------------------------------------------------- |
| SUDO_USERNAME                     | Superuser's username                                                                                  |
| SUDO_PASSWORD                     | Superuser's password                                                                                  |
| ROOT_DIR                          | Путь к установочным файлам																			|

По-умолчанию:
- ROOT_DIR: "/opt/marzban"
- SUDO_USERNAME: "admin"
- SUDO_PASSWORD: "admin"

### Главное меню
![image](https://github.com/zZeleZz/playbooks/assets/99475797/8d3fb1f0-a14a-4b3e-89ec-5029cae5e400)

### Страница подписки
![image](https://github.com/zZeleZz/playbooks/assets/99475797/61d1fcdb-d333-450a-968a-85c31b78b22c)

