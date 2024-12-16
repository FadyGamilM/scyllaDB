# scyllaDB
just leanring new distirbuted databsae which is scyllaDB


# Essentials 
- Designed for high-throughput and low latency
- Higher than other dbs by 10x 
- handle 1 Million Reads/Writes operations per node per second (so we can do some parallelization to get more performance i think)
- ScyllaDB is very good for high performance applications (< 10ms latency and highly throughput)

### What scyllaDB's choise at the CAP ? 
- SchyllaDB prefers the `Availability` and `Network partitioning` over `Consistency`

### What NoSql type we can classify ScyllaDB as ? 
- ScyllaDB is a `Wide Column` store database (not just document store database)

### Is ScyllaDB follows the leader-follower architecture ? 
![alt text](image.png)

### Consistent Hashing in ScyllaDB : 
- To be able to find which node contains ur data, ScyllaDB uses a consistent hashing (partitioner) mechanism

![alt text](image-1.png)
 
### Replication Facotr in ScyllaDB:
![alt text](image-2.png)


