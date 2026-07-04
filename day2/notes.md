docker --version
docker info
docker pull hello-world
docker images
docker run hello-world
docker ps
docker ps -a
docker rm <container_id>
docker rmi hello-world



# Docker commands.

We checked whether Docker is installed using docker --version and confirmed Docker engine details using docker info. Then we downloaded the hello-world image using docker pull, checked available images using docker images, and created our first container using docker run hello-world. We learned that an image is only a stored package, while a container is created when we run that image. We also learned that docker ps shows running containers, docker ps -a shows all containers, docker rm removes containers, and docker rmi removes images.