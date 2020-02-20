# app-security
Sample spring security based microservice


Steps to run 

1. Clone the repo

2. Run following commands

2.1	Linux
./mvnw spring-boot:run
2.2 Windows
mvnw spring-boot:run

Powershell
.\mvnw spring-boot:run

3. Test the basic authemtication by using
curl -u user:<password_generated_with springsecurity> http://localhost:8080/hello
