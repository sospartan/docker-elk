# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:7.0.0-beta1


RUN logstash-plugin install logstash-filter-prune
RUN logstash-plugin install logstash-input-lumberjack
RUN logstash-plugin install logstash-filter-range
RUN logstash-plugin install logstash-codec-avro
# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
# RUN logstash-plugin update logstash-input-beats
# RUN logstash-plugin update logstash-input-jdbc
# RUN logstash-plugin update logstash-output-elasticsearch
