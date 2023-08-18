FROM docker.elastic.co/logstash/logstash:6.8.23

RUN bin/logstash-plugin install logstash-output-amazon_es logstash-output-opensearch

# RUN cp /usr/share/logstash/vendor/bundle/jruby/2.5.0/gems/logstash-output-opensearch-1.2.0-java/lib/logstash/outputs/opensearch/templates/ecs-disabled/1x.json /usr/share/logstash/vendor/bundle/jruby/2.5.0/gems/logstash-output-opensearch-1.2.0-java/lib/logstash/outputs/opensearch/templates/ecs-disabled/6x.json
