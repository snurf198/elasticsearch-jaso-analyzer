FROM docker.elastic.co/elasticsearch/elasticsearch:8.13.4

COPY jaso-analyzer-plugin-8.13.4-plugin.zip /tmp/
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install file:///tmp/jaso-analyzer-plugin-8.13.4-plugin.zip