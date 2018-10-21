#Creación de imagen Docker con Dockerfile 

Comando para construir el contenedor a partir de dockerfile
- docker build -t "theparkz2/orbis-training-docker:0.1.0" . 

Comando para subir la imagen de docker a DockerHub 
- docker push "theparkz2/orbis-training-docker:0.1.0" 

Comando para cambiar de versión de Docker imagen 
- docker tag theparkz2/orbis-training-docker:0.1.0 theparkz2/orbis-training-docker:0.2.0
