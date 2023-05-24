# stack
1. Java
  - [Spring](https://spring.io/) возможности Microservices + Web apps  
    пример кода:
`
    @SpringBootApplication
    @RestController
    public class DemoApplication {
        @GetMapping("/helloworld")
        public String hello() {
            return"Hello World!";
        }
    }
`
