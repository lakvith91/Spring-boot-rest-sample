# Spring-boot-rest-sample
Spring Boot Rest Controller Sample Application

### Spring Boot Simple Rest Controller

    @RestController
    public class HelloController {
    
      @RequestMapping("/")
      public String index() {
         return "Greetings from Spring Boot!";
       }   
    }


### Build Sample project

    mvn clean install
    
### Run project

 Navigate to Target Folder in the project Folder
 
    java -jar gs-spring-boot-0.1.0.jar
    
    http://localhost:8080/
