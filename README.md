this application is running on port 8080
this application required on mysql db with docker image version mysql:8.0
docker run -d --name mysql-database-container1  -e MYSQL_ROOT_PASSWORD=root -p 3306:3306 mysql:8.0

for every java app, we have one application.properties file, you can find the required details more on that file all db information, it's standard in world wide

this java with mavenbuild and it's spring boot application
to build this code, you need openjdk17 version
