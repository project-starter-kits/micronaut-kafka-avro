# micronaut-kafka-avro
This kit enables creating Micronaut based kafka producer-consumer using Apache Avro schema registry,


## pre-requisite
This kit assumes that you have already have Micronaut & JDK installed on your system. References are given below.

### Steps
1. create a micronaut project using following command. 
mn create-app micronaut-kafka-producer --features=kafka --features=file-watch --lang groovy

from above, *create-app* Creates an Application (you can also try create-cli-app ). * *micronaut-kafka-producer* * is the name of skeleton project, * * features* * please refer to micronaut help for available features, above command creates a project enabled with Kafka and file-watch. (file watch watches for any changes in the source and stop / restart the project execution automatically). * *lang* * you can choose Groovy, Java or Kotlin


