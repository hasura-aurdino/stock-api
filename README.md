 stock-api
 
> SOFTWARE REQUIRED:
 
 
Java8 JDK or Java10 JDK (this project was built with jdk10)
Apache Maven
MongoDB
 
 
> Run API Service Locally
Run the following in the root directory:

Windows

mvnw.cmd clean install
mvnw.cmd spring-boot:run

MacOS
./mvnw clean install
./mvnw spring-boot:run

Links
Swagger
UI: http://localhost:8080/swagger-ui.html

API Spec: http://localhost:8080/v2/api-docs
extracted YAML and JSON under /src/main/resources/static directory
Stock Data: http://localhost:8080/api/v1/stocks
Spring Actuators
Health: http://localhost:8080/health
Metrics: http://localhost:8080/metrics
Http Trace: http://localhost:8080/httptrace
Mappings: http://localhost:8080/mappings

