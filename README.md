# NMAP

скрипты для сканирования уязвимостей

script vuln -p 80 ip 

скрипты уязвимостей nmap [host] --script vuln -sV 

https://github.com/SkillfactoryCoding/HACKER-OS-nmap.vulners https://github.com/SkillfactoryCoding/HACKER-OS-vulscan

-Pn - отключить пинг сканирование (обратится к хосту как будто он есть)

-sV - выполнить проверку версионности служб

-sS- syn сканирование

-A - агрессивное сканирование со скриптами - определяет все что можно

-sC - скрипты по умолчанию

sudo nmap -sU 10.129.77.175  - сканирование UDP портов

--min-rate 1000 минимальное число пакетов
