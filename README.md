### Running SpringBoot's Embedded Tomcat Servlet
- `mvn clean compile`
- `mvn spring-boot:run`

### Running Packaged WAR on External Tomcat Servlet
- `mvn clean package`
- retrieve custom-spring-boot-servlet-initializer-war.war file from target/ directory
- place it into tomcat's `libexec/webapps`
- start or restart tomcat server
- open browser: http://localhost:8080/custom-spring-boot-servlet-initializer-war
- if you see `hello world` then success!