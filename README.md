# Proyecto Docker Compose
Este proyecto cuenta con un docker compose el cual levanta automaticamente todos los servicios disponibles en este proyecto, ya que todos estan interconectados.
* Descargar o clonar el archivo
* Ejecutar el comando dentro del archivo docker compose **docker compose -f "Docker-compose.yml" up -d --build**
* Visualizar que los componentes esten levantados correctamente

Cuando tenga ejecute el comando va a observar que tiene los siguiente contenedores 
![image](https://github.com/Anthonazo/DockerCompose/assets/118082256/cd1fcc18-a97a-40d7-ba1a-a03f67233a94)

Puede acceder a cada uno para comprobar su funcionalidad 

* Jaeger: Acceder a localhost:16686
![image](https://github.com/Anthonazo/DockerCompose/assets/118082256/8a24c130-9cd3-4109-9ece-ace9b4a8facf)

* Wildfly: Acceder a localhost:8080
![image](https://github.com/Anthonazo/DockerCompose/assets/118082256/ea7019b1-9612-41e3-9e3d-7dd168b1cdd3)

* Angular: Acceder a localhost:4200
![image](https://github.com/Anthonazo/DockerCompose/assets/118082256/7008fafc-bc53-4b1a-a8eb-8051b5bb1421)

* Swagger: Acceder a localhost:8081 **COPIAR ESTE ARCHIVO JSON QUE SE CREA AUTOMATICCAMENTE AL INICIALIZAR WILDFLY: http://localhost:8080/api/openapi.json** ya que este permite visualizar
dicho json y probar los endpoints, debe tener como se visualiza en la imagen
![image](https://github.com/Anthonazo/DockerCompose/assets/118082256/e5234340-adc9-40f5-952d-d1f867e83a9c)

* PgAdmin: Acceder a localhost:5050
![image](https://github.com/Anthonazo/DockerCompose/assets/118082256/069ca7c1-43bb-4a22-94eb-e1f9189d5eb7)
