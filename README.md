#TAXI-SERVICE
###[View a demo](https://taxi-service-v.herokuapp.com/)

---

##Table of contents
* [About a project](#about-a-project)
* [Technologies](#technologies)
* [Setup](#setup)
***

##About a project
<a id="about-a-project"></a>

Taxi-service it's a __web application__.<br>
Basic implementation of a taxi service.
Allows you to use basic __CRUD operations__,
as well as __create__, __authenticate__ and __authorize__ a new drivers,
add a cars and a manufacturers to the __database__.
Other than key __CRUD__ operations there are other __features__ like adding 
driver to a car and showing a list of cars for currently logged in driver.
It is a training project that was created to show my skills in __JavaCore__, __JDBC__, and __Web__.

_I do not use "Hibernate" and "Spring Framework" 
to better understand how a web application works in more depth_.
***

##Technologies
<a id="technologies"></a>

* [Java 11](https://en.wikipedia.org/wiki/Java_(programming_language))
* [MySQL](https://en.wikipedia.org/wiki/MySQL)
* [JDBC](https://en.wikipedia.org/wiki/Java_Database_Connectivity)
* [JSP](https://en.wikipedia.org/wiki/Jakarta_Server_Pages)
* [JSTL](https://en.wikipedia.org/wiki/Jakarta_Standard_Tag_Library)
* [Java Servlets](https://en.wikipedia.org/wiki/Jakarta_Servlet)
* [Apache Log42j](https://en.wikipedia.org/wiki/Log4j)
* [Apache Tomcat 9.0.50](https://en.wikipedia.org/wiki/Apache_Tomcat)
***

##Setup.
<a id="setup"></a>

__To run this application please install:__
* [IntelliJ IDEA Ultimate](https://www.jetbrains.com/lp/intellij-frameworks/)
* [MySQL](https://dev.mysql.com/downloads/)
* [Tomcat](https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/)

__Further__
* Fork this project and clone it.
* Create schema in your "MySQL Workbench" using init_db.sql file.
*Add your personal info to ConnectionUtil class to connect to your database.
* Add Tomcat 9.0.50 configuration.

_If you wanna connect this project to your database, 
just add all the necessary information in the:_

```
src/main/java/mate/util
```

```Java
public class ConnectionUtil {
    private static final String URL = "YOUR CONNECTION URL";
    private static final String USERNAME = "YOUR LOGIN";
    private static final String PASSWORD = "YOUR PASSWORD";
    private static final String JDBC_DRIVER = "JDBC DRIVER";
}
```
