<!-- Based on [Course Developing APIs with Java, Spring Boot and MongoDB](https://youtube.com/playlist?list=PL5X822QTM1JYvV-osYuBH9FBq5rOO81Ea&feature=shared) -->

### Objective
* Creation of a simple REST API / CRUD for Student entity manipulation.

### Technologies used
* Java 21
* SpringBoot 
* MongoDB 
* Spring Cloud OpenFeign used [to consume a CEP search API](https://brasilapi.com.br/)
* JSON
  
### Implemented patterns
* DTO (Data Transfer Object): Used to transfer data between layers or services.

### Architecture used
*  REST (GET, POST, PUT, DELETE, PATCH)
*  MVC layered architecture (Model-View-Controller)
    * Controller: User interface layer. Where we receive requests.
    * Service: Business or application layer. Contains business logic and manages operations between repositories and controllers.
    * Repository: Data persistence layer. Contains methods that interact directly with the database.
    * Model: Domain layer or entities (data representations mapped to the database).
    * DTO: Serves as an intermediary to transfer data efficiently.