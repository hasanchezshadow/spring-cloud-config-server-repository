# Running the application
- Please enter the correct credentials in twitter4j.properties file.
- Then run mvn install -DskipTests command
- Then go to docker-compose folder and run docker-compose up command to run kafka cluster and twitter-to-kafka-service together
- Check twitter-to-kafka-service, where we added spring-cloud-starter-config dependency and added bootstrap.yml file
to configure the service to use config server