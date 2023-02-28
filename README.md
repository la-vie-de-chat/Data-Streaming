# Data Streaming 
End to End Data Streaming for Sentiment Analysis with Kafka, Spark and Cassandra

Kafka is the data pipeline. - Zookeeper </br>
Spark is the data streaming tool. - Master, worker, SparkSubmit </br>
Cassandra is the NoSQL database. </br>
Tomcat is the server. </br>
AWS EC2 is the running environment. </br>


## Architecture

   App
 _ _ _ _ _ 
|         |                     streaming
|         | --> Kafka --> Spark ----------> Cassandra
|_ _ _ _ _|     /   \       /
        \_ _ _ /     \_ _ _/
          Producer  Consumer
          (Java)     (Java)
