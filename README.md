# Домашнее задание к занятию "`Система мониторинга Zabbix. Часть 2`" - `Динейко Алексей`


---

### Задание 1

`Создан свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.`


```


1. ![Скриншот-1](https://github.com/Neoju5t/zabbix2/blob/836040c454619aaa3132bb68063ee8af4422f180/img/1zadanie.jpg)


---

### Задание 2

`Установка Zabbix Agent на два хоста`

```
sudo -s
wget https://repo.zabbix.com/zabbix/6.0/ubuntu/pool/main/z/zabbix-release/zabbix-release_latest+ubuntu22.04_all.deb
dpkg -i zabbix-release_latest+ubuntu22.04_all.deb
apt update
apt install zabbix-agent
systemctl restart zabbix-agent
systemctl enable zabbix-agent

```

![Скриншот-3](https://github.com/Neoju5t/zabbix_1/blob/be9541c6e9d17e73429d895e4f29171053b623be/img/Test2.JPG)
![Скриншот-4](https://github.com/Neoju5t/zabbix_1/blob/be9541c6e9d17e73429d895e4f29171053b623be/img/log.JPG)
![Скриншот-5](https://github.com/Neoju5t/zabbix_1/blob/be9541c6e9d17e73429d895e4f29171053b623be/img/connect%20server.JPG)


---
