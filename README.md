# :oncoming_taxi: Taxi-Service :oncoming_taxi:
### Project description:
```
A simple web-application that supports authentication, registration and other CRUD operations.
```
## :gear: Features:
- registration like a driver;
- authentication like a driver;
- create/update/remove a manufacturer;
- create/update/remove a car;
- create/update a driver;
- display list of all manufacturers;
- display list of all cars;
- display list of all drivers;
- display list of all cars by current driver;
- add driver to car.
## :note: Project structure (3-layer architecture):
- DAO - Data access layer
- Service - Application logic layer
- Controllers - Presentation layer
## :gear: Used technologies and libraries:
- Java 19
- Git
- Apache Maven
- Apache Tomcat
- MySQL
- JDBC
- Javax Servlet
- JSP
- JSTL
- HTML/CSS
- Checkstyle plugin
## :foot: Steps to run the program on your computer:
- Clone the repo [from here](https://github.com/Maks4u/taxi-service-by-maks4u.git);
- Install MySQL;
- Configure Apache Tomcat version (**IMPORTANT**): 9.0.5;
- Copy and run SQL script [/src/main/resources/init_db.sql](/src/main/resources/init_db.sql) to creating a schema and tables for the project;
- Configure [/src/main/java/taxi/util/ConnectionUtil.java](/src/main/java/taxi/util/ConnectionUtil.java) with your URL, USERNAME, PASSWORD, JDBC_DRIVER;
- Done. Now just try to use it. :tada: