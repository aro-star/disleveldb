# DisLevelDB 

DislevelDB is a high-performance NoSQL database library and server written in [Go](http://golang.org). It stores key value data in a disk. It uses Redis protocol and exhibits high performance which can be used in production. 

I would consider to edit the open source tool LedisDB.LedisDB supports LevelDB where you can enter string based key and value pair.
This repository consist of Ledis DB + Redis-Failover + Xcodis and raft algorithm which are main components of this design.

Raft algorithm is used to manage the consensus problem in high performance fault tolerant distributed system.

Refer link for more details:
https://raft.github.io/

Refer following link for ledisdb review which is a open tool.
https://stackshare.io/ledisdb

S/W Architecture:

![image](https://user-images.githubusercontent.com/85771488/121765534-51ef2e00-cb00-11eb-81ed-36e7864a6420.png)










