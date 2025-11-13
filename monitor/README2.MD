# System Status Monitor

![Bash](https://img.shields.io/badge/Bash-Script-green.svg)
![Linux](https://img.shields.io/badge/Platform-Linux-blue.svg)
![Monitoring](https://img.shields.io/badge/System-Monitoring-orange.svg)

Простой и эффективный bash-скрипт для мониторинга основных параметров системы Linux. Предоставляет краткий обзор ключевых метрик производительности.

## Назначение

Скрипт отображает основные показатели системы:
- Время работы (uptime)
- Использование дискового пространства
- Использование оперативной памяти
- Наиболее ресурсоемкие процессы
- Температуру процессора (при наличии датчика)

## Использование

```bash
# Сделать скрипт исполняемым
chmod +x system_status.sh

# Запустить
./system_status.sh
