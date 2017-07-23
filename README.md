# USCIS Hello World App

This is a very simple Spring Boot web app which largely borrows from the standard Gradle - Spring Boot Hello World app found at https://spring.io/guides/gs/spring-boot/.

## Pre-requisites
* Java 1.8
* Gradle 2.5+

## Build

`gradle build`

## Run

`java -jar .\build\libs\uscis-hello-0.1.0.jar`

**Expected output:**

```
2017-07-22 15:03:12.647  INFO 18368 --- [           main] o.s.j.e.a.AnnotationMBeanExporter        : Registering beans for JMX exposure on startup
2017-07-22 15:03:12.742  INFO 18368 --- [           main] o.s.c.support.DefaultLifecycleProcessor  : Starting beans in phase 0
2017-07-22 15:03:13.421  INFO 18368 --- [           main] o.e.j.s.h.ContextHandler.application     : Initializing Spring FrameworkServlet 'dispatcherServlet'
2017-07-22 15:03:13.431  INFO 18368 --- [           main] o.s.web.servlet.DispatcherServlet        : FrameworkServlet 'dispatcherServlet': initialization started
2017-07-22 15:03:13.548  INFO 18368 --- [           main] o.s.web.servlet.DispatcherServlet        : FrameworkServlet 'dispatcherServlet': initialization completed in 117 ms
2017-07-22 15:03:13.659  INFO 18368 --- [           main] o.e.jetty.server.AbstractConnector       : Started ServerConnector@46baf579{HTTP/1.1,[http/1.1]}{0.0.0.0:8080}
2017-07-22 15:03:13.660  INFO 18368 --- [           main] .s.b.c.e.j.JettyEmbeddedServletContainer : Jetty started on port(s) 8080 (http/1.1)
2017-07-22 15:03:13.723  INFO 18368 --- [           main] gov.uscis.devsecops.hello.HelloApp       : Started HelloApp in 10.443 seconds (JVM running for 11.187)
2017-07-22 15:06:33.102  INFO 18368 --- [tp1187410086-20] s.b.a.e.m.MvcEndpointSecurityInterceptor : Full authentication is required to access actuator endpoints. Consider adding Spring Security or set 'management.security.enabled' to false.
```
