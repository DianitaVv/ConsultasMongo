# Comandos para ejecutar un contenedor Docker
## Instalar la imagen

docker pull mongodb/mongodb-community-server:latest


**crear un nuevo contenedor**
docker run --name mongoserver -d -p 27017:6000 nombreimagen

**ver los contenedores**
docker ps -a

**ver los contenedor que se ejecutan**
docker ps

**entrar a mongosh**
docker exec -it mongoserver mongosh

**eliminar una imagen**
docker rmi nombreimagen

**eliminar un contenedor**
docker rm nombrecontenedor





