### 2017-04-05

#### TimescaleDB

https://www.timescale.com/

An open-source time-series database optimized for fast ingest and complex queries. Looks, feels, speaks like Postgres.


### 2017-03-23

#### Hash indexes are faster than Btree indexes?

https://amitkapila16.blogspot.kr/2017/03/hash-indexes-are-faster-than-btree.html

This blog will mainly focus on the search operation. By definition, hash indexes are O(1) and Btree indexes are O(log n), however with duplicates that is not exactly true.

The important thing to note about the above data is that it is only on some of the specific workloads and it mainly covers Selects as that is the main area where performance improvement work has been done for PostgreSQL10.