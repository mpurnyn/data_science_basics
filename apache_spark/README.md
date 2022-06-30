### Apache Spark Overview

It is a Data Processing engine
**General**
- in-memory execution
- fast iterative access to datasets
- data workers can efficiently execute streaming, ML, or SQL
- easy to combine different processing models seamlessly in the same application
    - example
        - ML library for data classification
        - Spark Streaming ffor streaming data through sorce
        - Spark SQL for querying data in real time
        - all al the same time and same application

**Speed**
- runs computation in memory
- Direct Acyclic Graph (DAG) Execution engine
    - acyclic data flow
    - in-memory computing
- hadoop clusters run 100 faster in memory and 10 times faster on disk than Map Reduce

