# parcial2-arquitectura
Parcial 2 Diseño y Arquitectura de software
Punto 6) a. 
Una vez Docker abierto:
Para crear una imagen con mysql se ponen los comandos: 
- docker run -d -p 3306:3306 -e `MYSQL_ROOT_PASSWORD=my-secret -e MYSQL_DATABASE=nombre`
- `$ docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mysql:tag`
