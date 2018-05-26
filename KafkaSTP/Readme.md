# H08 - Java Kafka

# Customized Kafka-Enabled App

# S528763 - Aditya Srimat Tirumala Pallerlamudi

My application is 'Tweeter'

Steps to run:
1. Run Zookeeper server
'zkServer'

2. Run Kafka server
.\bin\windows\kafka-server-start.bat .\config\server.properties

3. Create the KafkaAPIClient Executable Jar
mvn clean compile assembly:single

4. Start the Default consumer and producer apps.
5. Type any content in producer and verify it in consumer command window.
6. Run your custom producer linked with run.properties
7. Verify the tweets of the respective user profile in the Consumer console.

For more usage of application, change the 'TWITTER_USER' to any other profile and erify the tweets. Have fun.

Useful links:
1. twitter.com
2. apps.twitter.com

Useful commands:
1. java -cp target/api.jar edu.nwmissouri.stp.kafka.CustomProducer test
2. java -cp target/api.jar edu.nwmissouri.stp.kafka.Consumer test group1

Thank you.
