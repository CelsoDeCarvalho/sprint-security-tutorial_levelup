# sprint-security-tutorial_level1
This is a tutorial for creating spring apps with spring security framework for beginners

### To make our application secure, we start by adding the spring security dependency in our pom.xml file
---

``
<dependency>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-starter-security</artifactId>
</dependency>
``

### Once the spring security dependency is added to our class path, sprig security does some automatic configuration like:

- Authentication
- login page
- Handling bad credentials login error
- Default user
---
### Spring security can be fully customized allowing the developer to configure the authentication and authorization process in the system, but by default spring security creates a user with username `user` and a new password is generated for each execution of the application and you can find it in the application execution terminal