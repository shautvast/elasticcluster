FROM docker.elastic.co/elasticsearch/elasticsearch:7.13.2
USER 1001
EXPOSE 9200/tcp
CMD ["bin/elasticsearch","-E","cluster.initial_master_nodes=node1"]
