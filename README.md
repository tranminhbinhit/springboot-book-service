# Rest CRUD Book API Spring Boot MySQL and Springdoc

## Configure Spring JPA
Open `src/main/resources/application.properties`.
Change your username and password according to your MySQL Database.

## Run Spring Boot application
```
mvn spring-boot:run
```

## Book APIs
| Methods | Urls           | Actions                |
|---------|----------------|------------------------|
| POST    | /api/books     | create new Book        |
| GET     | /api/books     | retrieve all Books     |
| GET     | /api/books/:id | retrieve a Book by :id |
| PUT     | /api/books/:id | update a Book by :id   |
| DELETE  | /api/books/:id | delete a Book by :id   |

## Swagger UI
- Access point: http://localhost:8080/swagger-ui/index.html?configUrl=/v3/api-docs/swagger-config
- Setup swagger ui: https://viblo.asia/p/tu-dong-hoa-tao-tai-lieu-api-su-dung-java-springdoc-va-swagger-ui-63vKjdaRl2R

## Description
- https://viblo.asia/p/deploy-spring-boot-cung-mysql-len-aws-gAm5yrNkKdb
