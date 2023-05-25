# stack
1. Java
  - [Spring](https://spring.io) + Spring Boot  
    _основные возможности_: API, микросервисы + веб приложения  
    _плюсы_:
    - универсальный, широко распространенный фреймворк с большим количеством модулей для Spring.
    - OpenJDK & [Axiom JDK](https://axiomjdk.ru/pages/about) (БЕЛЛСОФТ, включена в Единый реестр российских программ)  
    - [JMIX](https://www.jmix.io/framework), [JMIX Access](https://www.jmix.io/ms-access-alternative) (возможно тоже в реестре).
    - есть наборы UI компонентов [Vaadin](https://vaadin.com/docs/latest/components)
    - среда для разработки IntelliJ IDEA Community.
    - docker friendly.
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
    _основные возможности_: open-source cross-platform GUI apps
    
2. Python
  - [Django](https://www.djangoproject.com), [Flask](https://flask.palletsprojects.com/en/2.3.x)  
    _основные возможности_: API, микросервисы, бэкенд + шаблонизаторы страниц  
    плюсы:
    - широко распространенные фреймворки.
    - огромное количество модулей (библиотек) для Python. [GeoPandas](https://geopandas.org/en/stable/docs/user_guide/mapping.html), можно использовать в ML, и как linux shell script (аналогично PowerShell в Windows) и т.д.
    - Python обычно есть в любых linux-дистрибутивах из коробки.
    - среда разработки PyCharm Community.
    - docker friendly.
    - простой язык (пример кода):
```
from flask import Flask  

app = Flask(__name__)  

@app.route("/")  
def hello_world():  
    return "<p>Hello, World!</p>"  
```
  - [Kivy](https://github.com/kivy/kivy), [wxWidgets](https://github.com/wxWidgets/wxWidgets), [Toga](https://github.com/beeware/toga)  
    _основные возможности_: open-source cross-platform GUI apps
  - [Dash](https://dash.plotly.com/dash-core-components) + [Dash in GitHub](https://github.com/plotly/dash) + [Plotly](https://plotly.com/python/maps)  
    _основные возможности_: создание богатого интерфейса на Python, "под капотом" Plotly.js, React and Flask

3. C#
  - [NET6]()  
    _основные возможности_: API, микросервисы + фронтенд (Blazor) + GUI (Uno/Gtk) 
    _плюсы_:
    - большое количество модулей (библиотек)
    - среда разработки Visual Studio Community
    - docker friendly
  - [UNO](https://github.com/unoplatform/uno) + [описание для linux](https://platform.uno/uno-platform-for-linux)  
    _основные возможности_: Mobile, Desktop and WebAssembly apps with C# and XAML 
  - [GtkSharp](https://github.com/GtkSharp/GtkSharp)
    _основные возможности_: C# Desktop = wrapper for Gtk 
