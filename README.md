# stack
1. Java
  - [Spring](https://spring.io/)  
    основные возможности: Microservices + Web apps  
    плюсы:
    - универсальный, широко распространенный фреймворк с большим количеством модулей (библиотек)
    - есть OpenJDK & [Axiom JDK](https://axiomjdk.ru/pages/about) (БЕЛЛСОФТ, включена в Единый реестр российских программ),  
    - среда для разработки IntelliJ IDEA Community Edition
    - docker friendly - декларируется поддержка создания приложений для "облака"
    - возможно использование технологий Kotlin (может компилироваться в JS), WebFlux (reactive programming), [jmix](https://www.jmix.io/ms-access-alternative/)
    - простой язык, пример кода:
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

  2. 
