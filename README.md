# Leer esto primero
Antes que nada, bienvenida a este repo para el ejemplo jejjeje

### Docker
docker run --name sqlServer -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=mydb -d -p 3306:3306 mysql
docker start sqlServer

La ip con la que se queda la máquina es la 192.168.99.100 esto lo puedes comprobar haciendo un docker-machine ip. En caso de que sea distinta, en el application.yml le cambias la ip y listo.
La url para acceder a la página es localhost:8080

### Credenciales
user: user
password: user

Hay que hacer un mvn clean install después de importarlo.
Y nada más.
