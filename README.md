# Spring-boot with frontend starter

### Requirements
* Java 1.7+
* Apache maven 3.1+
* Node.js

### Usage
#### For developer's local mode
```
$ npm install
$ ./mvnw clean spring-boot:run &
$ npm run watch
```

#### For production mode
```
$ ./mvnw clean package
$ java -jar ./target/spring-boot-with-frontend-stater-0.0.1-SNAPSHOT.war
```
