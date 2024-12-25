# MICROSERVICE_HW1

Данная работа выполнена студентом УРФУ Моисеевым Данилой.

Архитектура проекта:

microservice_architecture/
├── docker-compose.yml        
├── features/                 
│   ├── Dockerfile
│   ├── requirements.txt
│   └── src/
│       └── features.py
├── model/                    
│   ├── Dockerfile
│   ├── requirements.txt
│   ├── myfile.pkl          
│   └── src/
│       └── model.py
├── metric/                   
│   ├── Dockerfile
│   ├── requirements.txt
│   └── src/
│       └── metric.py
├── plot/                     
│   ├── Dockerfile
│   ├── requirements.txt
│   └── plot.py
└── logs/                    


Результаты работы:

RabbitMQ - http://localhost:15672 (guest/guest)
Метрики сохраняются в файл: logs/metric_log.csv
График распределения ошибок: logs/error_distribution.png
