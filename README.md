# easy_start
Набор файлов для быстрого развертывания решений на базе докер контейнеров


Для редис:

cd redis
sudo mkdir data
sudo mkdir data/{bases,log}

sudo docker-compose up --build


Для постгресс:

cd postgresql
sudo mkdir postgres_data

sudo docker-compose up --build