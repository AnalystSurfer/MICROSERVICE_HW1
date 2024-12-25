# MICROSERVICE_HW1

Данная работа выполнена студентом УРФУ Моисеевым Данилой.

Архитектура проекта:


docker-compose.yml    

features/                 
├── Dockerfile

├── requirements.txt

└── src/└── features.py

logs/                     
├── error_distribution.png

├── metric_log.csv


model/                    
├── Dockerfile

├── requirements.txt

├── myfile.pkl        

└── src/└── model.py

metric/                   
├── Dockerfile

├── requirements.txt

└── src/└── metric.py

plot/                     
├── Dockerfile

├── requirements.txt

└── plot.py
                 


Результаты работы:

RabbitMQ - http://localhost:15672 (guest/guest)

Метрики сохраняются в файл: logs/metric_log.csv

График распределения ошибок: logs/error_distribution.png
