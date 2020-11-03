# Pasos a seguir para levantar un docker con Apache, PHP, mysql y phpmyadmin

1. Comprueba tu instalación de docker con: docker -v
2. Revisa en el archivo yaml la configuración de los componentes.
3. Levanta el contenedor con: docker-compose up -d (segundo plano)
4. Para ver cómo se ejecuta el contenedor: docker ps
5. Comprueba si phpmyadmin y el servidor apache responden. 
5. Para acceder al contenedor con unterminal interactivo: 
    docker container exec -it [docker_container_name] /bin/bash (tipo de shell)
4. Para el contenedor con: docker-compose down
