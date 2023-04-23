# Running the application
- Please enter the correct credentials in twitter4j.properties file.
- Then run mvn install -DskipTests command
- Then go to docker-compose folder and run docker-compose up command to run kafka cluster and twitter-to-kafka-service together
- Check twitter-to-kafka-service, where we changed the bootstrap.yml file to use the remote github repository,
please update the github url and username/password in bootstrap.yml file, and connect your config-server-repository to
your private github repository