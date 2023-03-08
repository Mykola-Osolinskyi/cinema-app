# Cinema web app
## Project description

The application is built on top of the Spring framework, which provides a flexible and modular architecture for building web applications. Hibernate is used as the ORM tool to map Java objects to database tables and vice versa.

The application supports user authentication and authorization using Spring Security. Users are required to log in to access the application's features, and their credentials are authenticated against a user database stored in a relational database using Hibernate.

Once authenticated, users can perform CRUD operations on various resources such as articles, products, or orders. The application exposes RESTful APIs for these operations, which can be consumed by client applications.
## Project structure
![scheme](https://user-images.githubusercontent.com/117721643/223648080-12a7290f-6cec-450d-83dd-92abc5855a7c.png)
## Project structure
* config - contains config classes required by Spring & Hibernate
* controller - all http controllers
* dao - classes responsible for crud operations with db
* dto - used for http requests and responses
* exception - custom exceptions
* lib - custom validators for email, password and confirm password
* model - model classes for entities shown in scheme above
* service - classes that are responsible for business logic and connecting dao with controllers
* service/mapper - mappers that are used to parse dto to entity and entity to dto
* util - util class containing date pattern to parse date from json 
## Technologies
* Java 17
* Spring Web MVC
* Spring Security
* Hibernate
* MySql
* Tomcat
* Maven
## How to run the app
* Clone this repo;
* Install MySQL;
* Configure Apache Tomcat version: 9;
* Run "mvn clean package" command in terminal;
* Start Tomcat.
## Waiting for your feedback! 
