# MediscreenApp
This is the main repository to include the other 4 parts (Patient, UI, Record, Report).
To start the project,
1, First import the other 4 parts into this repository.
2, Then define a local repository to persist mysql data, replace what has been defined in docker-compose `/Users/lime/mediscreen-patient` as your own local repository.
3, Create a new volume in terminal: `$ docker volume create mongodbdata`.
4, Check if any variables in docker-compose need to be modified as your own: username, password.
5, Now start the project with command: `$ docker-compose up -d --build`.
6, Check the project on URL: `http://localhost:8080/`.
7, Check Swagger documentations: `http://localhost:8081/swagger-ui/index.html#/`, `http://localhost:8082/swagger-ui/index.html#/`, `http://localhost:8083/swagger-ui/index.html#/`.
