# A Blueprint for all of your future Spring-Boot projects
This template repository is used for generating Spring Boot projects. It has all the essentials to get started right away. 

No need to create the project, add dependencies this and that. Just create a repository with this template and change the name.
- Spring Boot version: **4.0.6**
- Java version: **25 LTS**
- Gradle version: **9.5.0**
____
### How to run the project
First you need to set up Docker locally and run the `docker-compose.yaml` file in terminal `docker compose up -d` which pulls `postgres-17alpine` image and creates a container which is the DB.
Each time you want to start the container, use this command `docker compose up -d`.

 After that run the application and visit this url `http://localhost:8181/swagger-ui/index.html` it will display Swagger UI that lists all the endpoints that has been created.
