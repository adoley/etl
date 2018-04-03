# etl
Extract from Messaging Queue, Transform(some transformation) and Load to messaging queue, NoSql etc. using spark/storm
#Prerequisite
java, maven
#Flow
Messaging Queue(kafka,zeroMQ,RabbitMQ etc.)--------Extract----Spark/Storm--(Transforn)-----Load----Messaging Queue/NoSQL(HBase/MangoDB etc.)
#Sample Message
Input Message(hello world 1)--------Transform(HELLO WORLD 1)--------Load(to MQ/NoSQL)
