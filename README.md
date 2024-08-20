# Spring Consuming Rest Service Guide

## Description
I have learned how to create a Spring consuming rest service from the official site.
https://spring.io/guides/gs/consuming-rest

**Lesson learned:**
- Create a simple consuming external API using Spring Boot.

## Run the Service

### Gradle

#### Run application

```sh
./gradlew bootRun
```

#### Alternative - Build JAR file

```sh
./gradlew build
```

```sh
java -jar build/libs/spring-rest-service-0.0.1-SNAPSHOT.jar
```

### Maven

#### Run application

```
./mvnw spring-boot:run
```

#### Alternative - Build JAR file

```
./mvnw clean package
```

```
java -jar target/spring-rest-service-0.0.1-SNAPSHOT.jar
```