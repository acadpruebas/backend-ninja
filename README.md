# Leer esto primero
Antes que nada, bienvenida a este repo para el ejemplo jejjeje
El código se podría mejorar pero la estructura está bastante decente.
La app es un simple CRUD web, uso un contenedor MYSQL para tener la base de datos y uso maven.

Si tienes docker el comando para que puedas tener el contenedor es el siguiente:
docker run --name sqlServer -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=mydb -d -p 3306:3306 mysql

Luego para arrancar el contenedor usas el siguiente comando:
docker start sqlServer

La ip con la que se queda la máquina es la 192.168.99.100 esto lo puedes comprobar haciendo un docker-machine ip. En caso de que sea distinta, en el application.yml le cambias la ip y listo.
No tengo mucho más que comentar sobre la app, no usa Angular, sino que los html están integrados usando thymeleaf. La url para acceder a la página es localhost:8080

Para el login:
user: user
password: user

Hay que hacer un mvn clean install después de importarlo.
Y nada más. Cualquier cosa mandame un correo