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
          
<img width="399" alt="Screen Shot 2023-03-06 at 8 09 39 PM" src="https://user-images.githubusercontent.com/70874534/223318580-6fd6d87e-a19a-4e73-b3ba-12fa57308d36.png">
