# Application name

Description of application and its goals.

Links/ports exposed with localhost links (Swagger...).

External dependencies (databases, services...).

Technological stack (requirements). Docker. Versions. Type of component...

# Other content

<<<<<<< HEAD
Relative links to MD.
=======
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
>>>>>>> d522429c25e05571c9c1cbb0f357a61f31e1dfd8

* []()