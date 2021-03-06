angularjs-springmvc-sample-boot
===============================

An example application using AnguarJS/Bootstrap as frontend and Spring MVC as REST API producer.

**This is a Spring Boot version of the original application.** If you are not ready for Spring Boot at the moment, please go to [angularjs-springmvc-sample](https://github.com/hantsy/angularjs-springmvc-sample) to get the original version.

In fact, this is an improved version which includes more features.

* Database based security config instead of the InMemory solution.
* Spring Data auditing is enabled.
* The new Java 8 DateTime(JSR310) is supported.
* Administration UI is included in this version which had been removed in the original version.

##Requirements

   * JDK 8

     Oracle Java 8 is required, go to [Oracle Java website](http://java.oracle.com) to download it and install into your system. 
     
     Optionally, you can set **JAVA\_HOME** environment variable and add *&lt;JDK installation dir>/bin* in your **PATH** environment variable.

   * Apache Maven
   
     Download the latest Apache Maven from [http://maven.apache.org](http://maven.apache.org), and uncompress it into your local system. 
    
     Optionally, you can set **M2\_HOME** environment varible, and also do not forget to append *&lt;Maven Installation dir>/bin* your **PATH** environment variable.  

## Run this project

   1. Clone the codes.

    <pre>
    git clone https://github.com/hantsy/angularjs-springmvc-sample-boot
    </pre>
  
   2. Instead of running this project via `mvn tomcat7:run` command, using `mvn spring-boot:run` here.
  
    <pre>
    mvn spring-boot:run
    </pre>

   3. Go to [http://localhost:9000](http://localhost:9000) to test it. If you want to explore the REST API docs online, there is a *Swagger UI* configured for visualizing the REST APIs, just go to [http://localhost:9000/swagger-ui.html](http://localhost:9000/swagger-ui.html).


