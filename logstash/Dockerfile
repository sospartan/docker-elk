# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash-x-pack:6.2.1


RUN logstash-plugin install logstash-filter-prune
# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
# RUN logstash-plugin update logstash-input-beats
# RUN logstash-plugin update logstash-input-jdbc
# RUN logstash-plugin update logstash-output-elasticsearch
