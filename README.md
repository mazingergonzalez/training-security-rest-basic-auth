## Spring Security REST Basic Authentication

This project showd the basic authentication with Spring Security on a REST simple api

### The Source theory

You can find a basic explanation in [https://www.baeldung.com/spring-security-basic-authentication](https://www.baeldung.com/spring-security-basic-authentication)

### Starting 

To run the container:

`$ mvn clean verify org.codehaus.cargo:cargo-maven2-plugin:run`

To access the secured API:

`http://localhost:8082/spring-security-rest-basic-auth/api/foos/1`

- usr: *user1*
- pwd: *user1Pass*

To access the non-secured API:

`http://localhost:8082/spring-security-rest-basic-auth/api/bars/1`

