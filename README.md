# todos-app
Manage Your Todos

### Docker Command Used for Database

docker run --detach --env MYSQL_ROOT_PASSWORD=root --env MYSQL_USER=todo --env MYSQL_PASSWORD=todo --env MYSQL_DATABASE=todos --name mysql --publish 3306:3306 mysql:8-oracle
