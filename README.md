This elasticsearch is for local development environment only.

## DO NOT use this on any environment like production, staging, qa environment

Elasticsearch configurations can be found
### ./docker/config/elasticsearch.yml

Kibana configurations can be found
### ./docker/config/kibana.yml


Setup

### 1. run "docker-compose up" or "docker-compose up --build"

Drop

### 1. run "docker-compose down -v"

Access bash
### 1. Get list of docker pid by "docker ps"
### 2. run "docker exec -it PID bash"


Services

### Kibana is hosted at http://localhost:5601
### Elasticsearch is hosted at http://localhost:9200