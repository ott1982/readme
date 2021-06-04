# Application name

Description, goals, tech stack, producers, consumers.

# Development

## Run application

```shell
mvn clean spring-boot:run
```

**Usage:**

* [Swagger UI](http://localhost:8080/swagger-ui.html).

## Run tests

Java libs used: JUnit 5 + Vintage (JUnit 4), Mockito and Assert4j.

```shell
mvn clean test
```

## Run Java Code Coverage

It uses JaCoCo:

```shell
mvn clean test -D jacoco.skip=false
```

## Run integration tests

```shell
mvn clean test -Pit
```

## Run application into Docker container

```shell
docker build -t appname:latest .
docker run -it --init --rm -p 8080:8080 appname:latest
```

**Usage:**

* [Swagger UI](http://localhost:8080/swagger-ui.html).

# Deployment

SSP?

Jenkins jobs?

...

# Appendix

## something...

