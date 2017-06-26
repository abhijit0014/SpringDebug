# Debugging Auto Configuration

### Debugging Auto Configuration

There are two ways you can debug and find more information about auto configuration.

* Debug logging
* Spring Boot Actuator

#### Debug Logging
You can turn debug logging by adding a simple property value to application.properties. 
```
logging.level.org.springframework: DEBUG
```

#### Spring Boot Actuator
Other way to debug auto configuration is to add spring boot actuator to your project. 
```
<dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-actuator</artifactId>
</dependency>
```
```
<dependency>
	<groupId>org.springframework.data</groupId>
	<artifactId>spring-data-rest-hal-browser</artifactId>
</dependency>
```

link :: http://localhost:8080/actuator
