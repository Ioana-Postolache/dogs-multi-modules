# Dogs multi modules

## Adding module from project
First, add the project add a submodule
`git submodule add https://github.com/<user>/rock rock`
In Intellij, go to File --> Project Structure
![Choose directory](images/Dogs%20-Import%20Module%20from%20Project.png)

Go to Modules -> Add module -> Import Module
![Add module](images/Dogs%20-%20Import%20project.png)

![Import module from existing model](images/Dogs%20-%20Import%20module%20from%20external%20model.png)


## Microservices
Only `dog-rest-and-graphql-api/src/main/java/com/udacity/bootstrap/repository/CatRepository.java` and `dog-rest-and-graphql-api/src/main/java/com/udacity/bootstrap/entity/Cat.java` were needed after adding 
``` 
<dependency>
  <groupId>org.springframework.boot</groupId>
  <artifactId>spring-boot-starter-data-rest</artifactId>
</dependency>
```
Testing cats microservices:
![Cats microservices](images/Cats%20-%20microservice.png)
