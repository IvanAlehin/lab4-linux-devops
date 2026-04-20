# Lab4 DevOps

## Автор
Алехин И.И., группа 6411

## Файлы
- `service.sh` - bash-скрипт для запуска HTTP-сервера
- `lab4-service.service` - systemd unit для автозапуска
- `lab4-healthcheck.sh` - скрипт проверки работоспособности
- `inventory.ini.example` - пример инвентаря для Ansible
- `site.yml` - Ansible playbook для развёртывания

1. Запуск сервиса: `sudo systemctl start lab4-service`
2. Проверка статуса: `sudo systemctl status lab4-service`

