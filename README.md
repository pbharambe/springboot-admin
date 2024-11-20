# SpringBoot Admin


For SpringBoot Admin add below dependencies
```xml
        <dependency>
			<groupId>de.codecentric</groupId>
			<artifactId>spring-boot-admin-server</artifactId>
		</dependency>
		<dependency>
			<groupId>de.codecentric</groupId>
			<artifactId>spring-boot-admin-server-ui</artifactId>
		</dependency>
```
For SpringBoot Admin Client add below dependency 
```xml
        <dependency>
			<groupId>de.codecentric</groupId>
			<artifactId>spring-boot-admin-starter-client</artifactId>
			<version>3.3.5</version>
		</dependency>
```
also add SpringBoot Admin application URL in property file as 
```properties
    spring.boot.admin.client.url=http://localhost:9090
```