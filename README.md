# monitoring-neo4j-prometheus-grafana
Docker-compose setup to test monitoring Neo4j Causal Cluster with Prometheus and Grafana

This is an example project accompanying GraphAware's blog post [Monitoring Neo4j and Procedures with Prometheus and Grafana - Part 2](https://graphaware.com/neo4j/2019/06/14/monitoring-neo4j-prometheus-part-2.html)

The purpose of this is to get up and running with testing a Neo4j Causal Cluster Monitoring solution based on Prometheus and Grafana

# Run
Simply clone the repository and type `docker-compose up`.

The script will install in the main repository folder a Neo4j cluster of 3 core members and 1 read replica, Prometheus and Grafana. Everything is  already set up to work out-of-the-box, including the provisioned dashboard. A really good starting point for experimenting! For more information read also our [Causal Cluster Quickstart](https://graphaware.com/neo4j/2018/01/03/casual-cluster-quickstart.html) post.
