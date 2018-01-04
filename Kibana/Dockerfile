FROM docker.elastic.co/kibana/kibana:6.0.0

WORKDIR /usr/share/kibana

USER root
ADD ./conf/kibana.yml /usr/share/kibana/config/
RUN chown kibana:kibana config/kibana.yml
USER kibana

