# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash-oss:6.2.2

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin update logstash-input-beats
RUN logstash-plugin update logstash-input-jdbc
RUN logstash-plugin update logstash-output-elasticsearch
RUN logstash-plugin install logstash-input-lumberjack
