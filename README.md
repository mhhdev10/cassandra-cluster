# Cassandra cluster with docker compose
create cassandra cluster with docker-compose

```
git clone https://github.com/mhhnull/cassandra-cluster
cd cassandra-cluster
```
and start cluster with this command

`docker compose up -d`


and check cluster health with this command

`docker exec -it cassandra-node1 nodetool status`
