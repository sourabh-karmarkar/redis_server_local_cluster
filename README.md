## Installation
- https://redis.io/docs/stack/get-started/install/mac-os/

## Creating a redis cluster locally
- https://redis.io/docs/management/scaling/#create-a-redis-cluster

## Steps to Start Redis Cluster locally
- Start all the redis instances given in the cluster-test folder then run the below command.
- Create redis cluster

    `redis-cli --cluster create 127.0.0.1:6479 127.0.0.1:6480 127.0.0.1:6481 127.0.0.1:6482 127.0.0.1:6483 127.0.0.1:6484`

- SSH into the redis cluster by specifying the port

    `redis-cli -c -p 6479`

- To check in cluster in running successfully fetch the cluster info

    `CLUSTER INFO`