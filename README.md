# stack
1. Java
  - [Spring](https://spring.io/)  
    основные возможности: Microservices + Web apps  
    пример кода:
```
    @SpringBootApplication  
    @RestController  
    public class DemoApplication {  
        @GetMapping("/helloworld")  
        public String hello() {  
            return"Hello World!";  
        }  
    }  
```
  - плюсы:
    - универсальный, широко распространенный фреймворк с большим количеством модулей (библиотек)
    - есть OpenJDK & Axiom JDK (БЕЛЛСОФТ, включена в Единый реестр российских программ) 
    - среда для разработки IntelliJ IDEA Community Edition
