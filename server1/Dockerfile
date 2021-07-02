FROM quay.io/public/openjdk:8u292
ADD https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-7.13.1-linux-x86_64.tar.gz
CMD ["elasticsearch-7.13.1/bin/elasticsearch","-E","cluster.initial_master_nodes=node1"]
