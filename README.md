# HomeLab

Персональная лаборатория по изучению системного администрирования, DevOps и построения современной инфраструктуры.

Главная цель проекта — не собрать как можно больше технологий, а научиться понимать, как они взаимодействуют между собой в реальной инфраструктуре и научиться диагностировать возникающие проблемы.

---

# Подход к обучению

Каждая новая технология изучается по одному принципу:

1. Изучение теории и принципов работы
2. Практическое внедрение в лабораторию
3. Диагностика возникающих неисправностей

# Инфраструктура

Хостовая система

- Windows 11
- Hyper-V

Виртуальные машины
    
Windows Server 2025 
 -Active Directory
 -DNS

Windows 11
-подключена к домену для проверок gpo

Ubuntu Server 24.04 LTS 
 -PostgreSQL
 -Nginx
 -PHP-FPM
 -Zabbix Server
 -Zabbix Frontend
 -Zabbix Agent2

Ubuntu Server 24.04 LTS
 -docker / docker-compose
 -Nginx (reverse proxy) 
 -Wordpress
 -mysql
 -prometheus
 -grafana
 -fail2ban
 -node exporter


# Освоенные технологии

## Linux

Практически изучено:

- работа с файловой системой;
- systemd;
- SSH;
- Bash;
- управление пакетами (APT);
- журналы системы;
- диагностика служб;
- работа с конфигурационными файлами.

---

## Windows Server

Настроено:

- Active Directory Domain Services;
- DNS;
- Organizational Units (OU);
- Group Policy (GPO);
- управление пользователями и группами;
- подключение рабочих станций к домену.

---

## Веб-сервер

Используется:

- Nginx

Изучено:

- структура конфигурации;
- Reverse Proxy;
- взаимодействие Nginx и PHP-FPM;
- диагностика ошибок.

---

## Базы данных

Используется:

- PostgreSQL

Практически выполнено:

- создание базы данных;
- создание пользователей;
- подключение сервисов;
- диагностика ошибок подключения.

---

## Мониторинг

Развернут стек мониторинга:

- Zabbix Server
- Zabbix Frontend
- Zabbix Agent2

Настроен мониторинг:

- Ubuntu Server;
- Windows Server.

---

## Git

Практически изучено:

- Git;
- GitHub;
- Repository;
- Commit;
- Branch;
- Merge;
- Working Tree;
- Staging Area;
- Remote Repository.

Используется для ведения документации и контроля изменений проекта.



# Выполненные проекты


## RocketDev Test

Практический инфраструктурный проект, созданный для выполнения тестового задания на позицию Junior DevOps Engineer.

Использованные технологии:

- Docker
- Docker Compose
- Nginx
- WordPress
- MySQL
- Prometheus
- Grafana
- Node Exporter
- Fail2Ban

Реализовано:

- многоконтейнерная инфраструктура;
- Reverse Proxy;
- HTTPS;
- мониторинг;
- защита SSH;
- ограничение доступа к административной панели WordPress;
- документирование проекта.

GitHub:
https://github.com/iluxa9800/rocketdev-test

---


# Roadmap

## Завершено

- ✅ Linux
- ✅ Windows Server
- ✅ Active Directory
- ✅ DNS
- ✅ Git
- ✅ PostgreSQL
- ✅ Nginx
- ✅ Zabbix
- ✅ Docker
- ✅ Docker Compose
- ✅ Prometheus
- ✅ Grafana
- ✅ Fail2Ban

## В процессе

- 🔄 Компьютерные сети (TCP/IP, DNS, маршрутизация)
- 🔄 Bash

## Планируется

- ⬜ GitLab CI/CD
- ⬜ Ansible
- ⬜ Backup
- ⬜ Kubernetes

---
