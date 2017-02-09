# Elasticsearch, Kibana, Logstash Syslog in Docker

Kibana Dashboard on http://localhost:5601

Elasticsearch http://localhost:9200

Logstash syslog listener on `127.0.0.1:5400`

Syslog forwarding config (`/etc/syslog.conf`):

    *.*  @127.0.0.1:5400


