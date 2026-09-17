* docker pull prom/node-exporter 
* docker pull prom/prometheus
* dokcer pull grafana/grafana
* mkdir prometheus
* cd prometheus
* vim docker-compose.yml
*  docker compose up -d
*  docker run -d --name prometheus -p 9090:9090 --network prometheus_default prom/prometheus
*  docker exec -ti prometheus sh
   vi /etc/prometheus/prometheus.yml this step because configration file in contaner and if container delete configration will delete
   vim prometheus.yml 
   
