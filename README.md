# Registration_Form_springboot_MongoDB_JWT
Registration Form using React, Spring Boot, MongoDB, and JWT Authentication

libraries need to install:

backend:

navigate to the below link

	https://start.spring.io

Project		- Maven
Language 	- Java
Spring Boot	- 3.5.7
Group		- com.example
Artifact	- backend
Name		- backend
Packaging	- Jar
Java Version	- choose according to your local java version 17 or 21

Add the following Dependencies:

Spring Web 
Spring Data MongoDB
Spring Boot DevTools

click generate and extract the ZIP file

replace the backend src file with extracted src file

Add the below BCrypt Dependency in pom.xml

<dependency>
    <groupId>org.springframework.security</groupId>
    <artifactId>spring-security-crypto</artifactId>
</dependency>


frontend:

npx create-react-app frontend

replace the src in frontend

database and collection will be automatically created 

don't need of any manual creation