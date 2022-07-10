# Crud-Spring-Hibernate-REST

Spring-Hibernate based RESTful web application having functionality of CRUD operation.

Tech Stack
HTML, CSS, JSP

Java 1.8, Spring 5, Spring MVC, Hibernate, RESTful webservice

MySQL workbench

Tomcat Server, Maven

Define db connection in : src/main/resources/persistence-mysql.properties

# Install POSTMAN

GET : http://localhost:8081/spring-crm-rest/api/customers

GET : http://localhost:8081/spring-crm-rest/api/customers/id

POST ->body ->RAW/JSON : http://localhost:8081/spring-crm-rest/api/customers

{
    "firstName": "Maria",
    "lastName": "Gomez",
    "email": "maria.gomez@luv2code.com"
}

DELETE : http://localhost:8081/spring-crm-rest/api/customers/ID
