# Spring Boot RESTful Web Service

This is a minimal RESTful web service built with Spring Boot and Java 17.  
It handles GET requests to `/greeting` and returns a JSON response.

## Run the Project

```bash
./mvnw clean package
java -jar target/restservice-0.0.1-SNAPSHOT.jar
```

Then open: 
- Default: http://localhost:8080/greeting → returns `Hello, World!`
- Custom name: http://localhost:8080/greeting?name=ABC → returns `Hello, ABC!`


## What I Practiced
    •    Spring Boot project structure
    •    Controller setup with @RestController and @GetMapping
    •    Parameter handling with @RequestParam
    •    JSON response using record
    •    Packaging with Maven and running .jar file

## To Do
    •    Add POST/PUT support
    •    Connect to a database (e.g., H2)
    •    Add Swagger/OpenAPI documentation
