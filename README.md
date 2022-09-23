**Following services are included:**
- mongodb: MongoDB (exposed port: 27017)
- arangodb: ArangoDB (exposed port: 8529)
- postgres14: PostgresSQL (exposed port: 5432)
- postgres12: PostgresSQL (exposed port: 5433)
- TimescaleDB: TimescaleDB (exposed port: 5434)
- pgadmin4: pgAdmin4 (exposed port: 9901)
- rabbitmq: RabbitMQ (exposed ports: 5672, 15672)
- elasticsearch: Elasticsearch (exposed ports: 9200, 9300)
- elasticsearch-noauth: Elasticsearch (exposed ports: 9200, 9300)
- fluentbit: FluentD (exposed ports: 24224)
- fluentd: FluentBit (exposed ports: 24224)

**Network**
- You have to manually create a docker network first:
`$docker network create mydevnetwork`