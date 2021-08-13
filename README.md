# sch1200
Что такое sch1200?
sch1200-это утилита для тестирования на проникновение в Ваш собственный, учительский аккаунт dnevnik.mos.ru
Установка на Linux/Termux:

apt update && apt upgrade
apt install python
git clone https://github.com/debianlab/antisch/
pip3 install requests
cd antisch && python3 index.py
Инструкция:
Перед запуском брутфорс атаки обязательно убедитесь что вы заполнили файл bd.txt собственной базой пароль, иначе атака не начнется.
Если вы хотите использовать свой словарь для брутфорса, то обязательно заполните файл bd.txt! Файл our_slovar.txt ни в коем случае не трогайте!

Запустите скрипт командой: python3 sch1200.py
