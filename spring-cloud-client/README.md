# Spring cloud client

## Getting Started

This application acts as a client that uses the server to obtain its own configuration

### Prerequisites

Java 7 or 8 installed on your machine

maven installed on your machine

### Installing

You just have to build the project using maven command : mvn clean install

In case you want to skip test use : mvn clean install -DskipTests

Then run the jar you got in your target : java -jar spring-cloud-server-0.0.1-SNAPSHOT


## Test

for test a rest controller was created that return a value retrieved from server

localhost:8002/lucky-word

## Built With

* [Java 8](http://www.oracle.com/technetwork/java/javase/overview/java8-2100321.html) - The java version used
* [Maven](https://maven.apache.org/) - Dependency Management
* [Spring boot](https://projects.spring.io/spring-boot/) - For embedded server and auto configuration

Contact me : karim.abdelmohsen.1992@gmail.com