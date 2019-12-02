# Hadoop Udemy


## Horton Sandbox

- username: maria_dev
- password: maria_dev
- terminal login: ssh maria_dev@127.0.0.1 -p 2222
- superuse: su root

## PIG
- Grunt
- Script
- Ambari/Hue
- Basic syntax: data = LOAD 'path' AS (column_name:d_type, ....);DUMP data;

### Commands
#### LOAD
- STORE
- DUMPSTORE ratings INTO 'outRatings' USING PigStorage(':'
- FILTER
- DISTINCT
- FOREACH/GENERATE
- MAPREDUCE
- STREAM
- SAMPLEJOIN
- COGROUP
- GROUP
- CROSS
- CUBEORDER
- RANK
- LIMIT
- UNION
- SPLIT
- AVG CONCAT COUNT MAX MIN SIZE SUM
#### Loaders
- PigStorage
- TextLoader
- JsonLoader
- AvroStorage
- ParquetLoader
- OrcStorage
- HBaseStorage
#### Diagnostics
- DESCRIBE
- EXPLAIN
- ILLUSTRATE
#### UDF's
- REGISTER
- DEFINE
- IMPORT
