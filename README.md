# Running the application
- Please enter the correct credentials in twitter4j.properties file.
- Then run mvn install -DskipTests command
- Then go to docker-compose folder and run docker-compose up command to run kafka cluster and twitter-to-kafka-service together
- Check logback-common.xml file in app-config-data module, where we created a common logback file and include it in 
twitter-to-kafka-service and config server