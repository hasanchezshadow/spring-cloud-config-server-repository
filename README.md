# Running the application
- Please enter the correct credentials in twitter4j.properties file.
- Then run mvn install -DskipTests command
- Then go to docker-compose folder and run docker-compose up command to run kafka cluster and twitter-to-kafka-service together
- Check twitter-to-kafka-service and config server, where we added spring-boot-starter-security dependency
and udpated bootstrap.yml file to include user name and password