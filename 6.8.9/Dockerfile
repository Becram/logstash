ARG VERSION

FROM docker.elastic.co/logstash/logstash:${VERSION}

ARG VERSION
ENV VERSION=${VERSION}


RUN bin/logstash-plugin install logstash-output-amazon_es

# RUN bin/logstash-plugin install  --version 6.4.2 logstash-output-amazon_es
