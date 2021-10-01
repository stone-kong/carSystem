# carSystem
Repository for REST API's

Maven is required to be able to run the project. For more information look [here](https://maven.apache.org/download.cgi)

# build 
mvn clean install 

# run 

Before you need to setup a mysql db. You can modify application.properties and then

mvn spring-boot:run

then you can start consuming the rest api
http://localhost:8080/car/findAll 