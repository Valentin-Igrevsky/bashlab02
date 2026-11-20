# bashlab02

![License](https://img.shields.io/github/license/Valentin-Igrevsky/bashlab02)
![Last commit](https://img.shields.io/github/last-commit/Valentin-Igrevsky/bashlab02)
![Repo size](https://img.shields.io/github/repo-size/Valentin-Igrevsky/bashlab02)
![Platform](https://img.shields.io/badge/platform-Kali%20Linux-557C94?logo=kalilinux&logoColor=white)
![Python](https://img.shields.io/badge/python-3.x-3776AB?logo=python&logoColor=white)
![Signed commits](https://img.shields.io/badge/commits-GPG%20signed-success)

Лабораторная работа 02: Linux - права доступа (chmod, chown, umask, ACL, SUID/SGID/sticky) и процессы.

## Файлы

| Файл                   | Назначение                               |
|------------------------|------------------------------------------|
| `pygamesteel.py`       | Исходный код с тремя ошибками            |
| `pygamesteel_fixed.py` | Исправленная версия                      |
| `nmapres.txt`          | Файл с ACL для результатов nmap (Lab 03) |
| `test_privesc.sh`      | Демонстрация SUID на скрипте             |

## Запуск

```bash
python3 -m venv .venv && . .venv/bin/activate
pip install pygame
python pygamesteel_fixed.py
```
