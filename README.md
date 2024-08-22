# Spring Consuming Rest Service Guide

Create a Spring consuming rest service.

https://spring.io/guides/gs/consuming-rest

---

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