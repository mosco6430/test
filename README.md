docker build -t mi-nginx-docker .
docker run --name mi-nginx-docker -d -p 8888:80 mi-nginx-docker
