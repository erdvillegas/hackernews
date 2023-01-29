# Tutorial de base de GRAP Api con Go
Ejemplo de aplocacion creado basado en el tutorial [graphql-go](https://www.howtographql.com/graphql-go/0-introduction/)

## Instrucciones para DB:
````
docker run -p 3306:3306 --name mysql -e MYSQL_ROOT_PASSWORD=dbpass -e MYSQL_DATABASE=hackernews -d mysql:latest
