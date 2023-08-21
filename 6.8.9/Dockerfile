ARG VERSION

FROM docker.elastic.co/logstash/logstash:${VERSION}

ARG VERSION

ENV VERSION=${VERSION}

COPY usage /usr/local/bin/usage

RUN bin/logstash-plugin install logstash-output-amazon_es
