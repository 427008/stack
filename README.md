# stack
1. Java
  - [Spring](https://spring.io)  
    основные возможности: микросервисы + веб приложения  
    плюсы:
    - универсальный, широко распространенный фреймворк с большим количеством модулей для Spring.
    - есть OpenJDK & [Axiom JDK](https://axiomjdk.ru/pages/about) (БЕЛЛСОФТ, включена в Единый реестр российских программ), [JMIX](https://www.jmix.io/framework), [JMIX Access](https://www.jmix.io/ms-access-alternative) (возможно тоже в реестре).
    - среда для разработки IntelliJ IDEA Community.
    - docker friendly - декларируется поддержка создания приложений для "облака".
    - возможно использование технологий Kotlin (может компилироваться в JS), WebFlux (reactive programming).
    - простой язык (пример кода):
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

  - [JavaFX](https://openjfx.io)
    основные возможности: open-source cross-platform GUI apps
    
2. Python
  - [Django](https://www.djangoproject.com), [Flask](https://flask.palletsprojects.com/en/2.3.x)  
    основные возможности: микросервисы, основной Python бакэнд + шаблонизаторы страниц  
    плюсы:
    - широко распространенные фреймворки.
    - огромное количество модулей (библиотек) для Python.
    - Python обычно есть в любых linux-дистрибутивах из коробки.
    - Среда разработки PyCharm Community.
    - docker friendly.
    - Python также можно использовать в ML, и как linux shell script (PowerShell).
    - простой язык (пример кода):
```
from flask import Flask  

app = Flask(__name__)  

@app.route("/")  
def hello_world():  
    return "<p>Hello, World!</p>"  
```
  - [Kivy](https://github.com/kivy/kivy)
    основные возможности: open-source cross-platform GUI apps
