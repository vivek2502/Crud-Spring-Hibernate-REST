# Crud-Spring-Hibernate-REST

Spring-Hibernate based RESTful web application having functionality of CRUD operation.

Tech Stack
HTML, CSS, JSP

Java 1.8, Spring 5, Spring MVC, Hibernate, RESTful webservice

MySQL workbench

Tomcat Server

Define db connection in : spring-mvc-crud-demo-servlet.xml
<bean id="myDataSource" class="com.mchange.v2.c3p0.ComboPooledDataSource" destroy-method="close">
      
    <property name="driverClass" value="com.mysql.cj.jdbc.Driver" />
    
    <property name="jdbcUrl" value="jdbc:mysql://localhost:3306/web_customer_tracker?useSSL=false&amp;serverTimezone=UTC" />
    
    <property name="user" value="springstudent" />
    
    <property name="password" value="springstudent" /> 

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
