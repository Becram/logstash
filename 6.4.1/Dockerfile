ARG VERSION

FROM docker.elastic.co/logstash/logstash:${VERSION}

ARG VERSION
ENV VERSION=${VERSION}

RUN bin/logstash-plugin install  --version ${VERSION} logstash-output-amazon_es
# RUN cp /usr/share/logstash/vendor/bundle/jruby/2.5.0/gems/logstash-output-opensearch-1.2.0-java/lib/logstash/outputs/opensearch/templates/ecs-disabled/1x.json /usr/share/logstash/vendor/bundle/jruby/2.5.0/gems/logstash-output-opensearch-1.2.0-java/lib/logstash/outputs/opensearch/templates/ecs-disabled/6x.json
# RUN cp /usr/share/logstash/vendor/bundle/jruby/2.5.0/gems/logstash-output-opensearch-1.2.0-java/lib/logstash/outputs/opensearch/templates/ecs-disabled/1x.json /usr/share/logstash/vendor/bundle/jruby/2.5.0/gems/logstash-output-opensearch-1.2.0-java/lib/logstash/outputs/opensearch/templates/ecs-disabled/6x.json
