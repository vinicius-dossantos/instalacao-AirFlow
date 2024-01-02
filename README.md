# instalacao-AirFlow
Instalacao do AirFlow no Windows para fins didaticos 

# Apache Airflow + Docker 
Docker utilizado para criação do Apache Airflow Localmente para uso didatico (provavelmente voce nao vera isso em producao).


## Requisitos
- Sistema Operacional Linux
- git               - https://git-scm.com/downloads
- docker            - https://docs.docker.com/get-docker/
- docker compose    - https://docs.docker.com/compose/install/

## Setup
```
git clone https://github.com/vinicius-dossantos/instalacao-AirFlow.git
```
```
mkdir -p /opt/airflow/dags /opt/airflow/logs /opt/airflow/plugins /opt/airflow/data

chmod -R 777 /opt/airflow
```
```
cd airflow
```
```
docker-compose up -d
```
## Default url
http://localhost:8080

## Default Username
airflow

## Default Password
airflow
