# First Project Using Java

## 1. Techonologies 

- Java +11 - https://www.java.com/pt-BR/
- Visual Studio Code - https://code.visualstudio.com/
- MVN - https://mvnrepository.com/
- Spring Boot - https://spring.io/tools
- Spring Boot Inicializr - https://start.spring.io/

## 2. Quick Start

### To initialize the database, use the following command:
```docker
docker run --name java-postgres-users -p 5432:5432 -e POSTGRES_PASSWORD=mysecretpassword -e POSTGRES_DB=spring_boot postgres
```
### To start the application, use the following command:
```
mvn spring-boot:run
```

## 3. Endpoints

- `POST` - http://localhost:8081/users/
- `GET` - http://localhost:8081/users/{id}
- `GET` - http://localhost:8081/users/list
- `GET` - http://localhost:8081/users/list/{id}
- `GET` - http://localhost:8081/users/findByName/{name}

## 4. Author

- [Lucas Lessa](https://github.com/LucasLessa14) - FullStack Web Developer

## 5. References

- [Aula 01](https://www.youtube.com/watch?v=UjQO3HSd6Ys)
- [Aula 02](https://www.youtube.com/watch?v=bWno9QpnGmk)