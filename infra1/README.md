# INFRA-1

##IMPORTANT!
```
If you're using docker-desktop (Win/Mac) make sure to allow more then 2GB of memory in settings.

Detail: Elasticsearch has also 2GB heap size, which means it exits shortly after start (with error 137)
```

### Services
- RabbitMQ
- Elasticsearch
- Logstash
- Kibana
- MongoDB

### Docker network
```
local-infra-net1
```
  
### RabbitMQ
- **Management**: http://localhost:15672
- **username**: rabbit
- **password**: rabbit

### Elasticsearch
- **Management**: http://localhost:9200
- **username**: elastic
- **password**: elastic_password

### Kibana
- **Management**: http://localhost:5601
- **username**: elastic 
- **password**: elastic_password

### Logstash
- Logging to stdout enabled in config file!

### MongoDB
- **Management**: http://localhost:27017
- **username**: admin 
- **password**: admin