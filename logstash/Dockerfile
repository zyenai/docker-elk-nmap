ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${ELASTIC_VERSION}

# Add your logstash plugins setup here
# Install logstash-codec-nmap. See https://www.elastic.co/guide/en/logstash/current/plugins-codecs-nmap.html
RUN logstash-plugin install logstash-codec-nmap