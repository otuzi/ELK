# ELK
### Задание 1. Elasticsearch 

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.

---
<img width="880" alt="Screenshot 2023-10-05 at 00 01 41" src="https://github.com/otuzi/ELK/assets/61628386/8270a5e5-4509-4ec3-a49b-4a39f8101f59">

---

### Задание 2. Kibana

Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty*.

---
<img width="903" alt="Screenshot 2023-10-05 at 00 05 41" src="https://github.com/otuzi/ELK/assets/61628386/66e18287-934e-4ee2-9cca-25ce226e89a1">

---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*

---
<img width="1274" alt="Screenshot 2023-10-05 at 00 14 22" src="https://github.com/otuzi/ELK/assets/61628386/3406b6de-0009-4438-88ba-925b4ad95b3c">

---

### Задание 4. Filebeat. 

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*

---
<img width="906" alt="Screenshot 2023-10-05 at 00 15 55" src="https://github.com/otuzi/ELK/assets/61628386/137e8220-fa5c-43e7-aabc-3239c8e09ece">

---
