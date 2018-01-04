FROM docker.elastic.co/elasticsearch/elasticsearch:6.0.0

USER root
ADD elasticsearch.yml /usr/share/elasticsearch/config/
RUN chown elasticsearch:elasticsearch config/elasticsearch.yml
USER elasticsearch
