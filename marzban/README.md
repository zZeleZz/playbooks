## Плейбук для установки прокси Marzban

Запуск:
```bash
ansible-playbook -i inventory playbook.yml```

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
