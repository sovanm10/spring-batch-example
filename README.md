#Spring Batch with Spring Boot3 and MySQL DB

### Reference Documentation
For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.1.3/gradle-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.1.3/gradle-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/3.1.3/reference/htmlsingle/index.html#web)
* [Spring Batch](https://docs.spring.io/spring-boot/docs/3.1.3/reference/htmlsingle/index.html#howto.batch)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)
* [Creating a Batch Service](https://spring.io/guides/gs/batch-processing/)

### Additional Links
These additional references should also help you:

* [Gradle Build Scans – insights for your project's build](https://scans.gradle.com#gradle)

###Overview

* DDL for my_test_db.user
```
CREATE TABLE `user` (
  `id` int NOT NULL,
  `name` varchar(45) DEFAULT NULL,
  `roll` varchar(45) DEFAULT NULL,
  `amount` double DEFAULT NULL,
  `class_name` varchar(45) NOT NULL,
  PRIMARY KEY (`id`)
) 
```


