# DisLevelDB 

-------
TASK 4 (software dev only)
--------

LevelDB is a fast key-value store developed by Google and now used as an
adapter for databases like PouchDB. However, it is only meant to
work on a single node. Implement a distributed LevelDB that is highly-available
and consistent.

DislevelDB is designed as high-performance NoSQL database which supports key value datastore. It exhibits high availability with consistency which makes it suitable for its use in production. 

I have used open source tool LedisDB. LedisDB supports LevelDB where we can use string based key and value pair.
This repository consist of Ledis DB + Redis-Failover + Xcodis and Raft algorithm which are main components of this architecture.

Raft algorithm is used to manage the consensus problem in high performance fault tolerant distributed system.

Refer link for more details:
https://raft.github.io/

S/W Architecture:

![image](https://user-images.githubusercontent.com/85771488/121766339-ec05a500-cb05-11eb-8b88-6b7d33a29806.png)











