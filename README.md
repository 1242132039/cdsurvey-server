# Reference
http://slackspace.de/articles/authentication-with-spring-boot-angularjs-and-keycloak/


# Configuration

## docker cmd
nohup  docker run  --name keyclaok -p 0.0.0.0:10110:8080 -p 10143:8843 -p 0.0.0.0:10111:9990 -e KEYCLOAK_USER=admin -e KEYCLOAK_PASSWORD=admin --rm  jboss/keycloak  &



# Authentication with Spring Boot, AngularJS and Keycloak

- Make sure to start Keycloak before using the application

## Run with standalone Tomcat

To run the project with embedded Tomcat by maven:

    mvn spring-boot:run
  
Then navigate to [http://localhost:8000](http://localhost:8000) to see the application in action.
docker cp  default_cmd.sh  ded4aa1378e3:/root/

docker commit -m "survey server" ded4aa1378e3 surveyserver:v1
s