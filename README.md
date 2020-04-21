# kafka
This is kafka , copy it into c drive to use it .There are 3 brokers which are already configured
cd C:\kafka\bin\windows

zookeeper-server-start.bat ..\..\config\zookeeper.properties

kafka-server-start.bat ..\..\config\server.properties

kafka-server-start.bat ..\..\config\server-1.properties

kafka-server-start.bat ..\..\config\server-2.properties

kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic library-events --from-beginning
