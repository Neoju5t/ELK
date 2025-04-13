# Домашнее задание к занятию "ELK" - `Динейко Алексей`


---

### Задание 1

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.



`Скриншот где виден нестандартный cluster_name`

![Скриншот-2](https://github.com/Neoju5t/ELK/blob/b3036a28ba65b7beb5a7a2e7b85e220cb7a230ec/img/1.PNG)

---

### Задание 2

Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

`Скриншот интерфейса Kibana`

![Скриншот-2](https://github.com/Neoju5t/ELK/blob/b3036a28ba65b7beb5a7a2e7b85e220cb7a230ec/img/2.PNG)


---

### Задание 3

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

`Скриншот с логами Nginx в Kibana`

![Скриншот-3](https://github.com/Neoju5t/ELK/blob/b3036a28ba65b7beb5a7a2e7b85e220cb7a230ec/img/3.PNG)

---

### Задание 4

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

`Скриншот с логами Nginx в Kibana через Filebeat`

![Скриншот-4](https://github.com/Neoju5t/ELK/blob/b3036a28ba65b7beb5a7a2e7b85e220cb7a230ec/img/4.PNG)
---
