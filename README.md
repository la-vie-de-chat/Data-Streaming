# Data Streaming 
End to End Data Streaming for Sentiment Analysis with Kafka, Spark and Cassandra

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

#Kafka #Zookeeper #Spark #NoSQL #Cassandra #Tomcat #AWS EC2
