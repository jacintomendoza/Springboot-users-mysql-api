# Springboot-users-mysql-api
Springboot example user application with full CRUD functionality.  Uses MySQL from a local database.

## Requires a MySQL database to be running. Docker was used to do this locally.

Command used to run docker container, test_sql, on an ARN M1 Mac.  Please change this according to your system.
```
docker run --name test_sql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=Password123 -d mysql --platform linux/x86_64 mysql
```

Update this if the above credentials are changed: src/main/java/resources/application.properties
