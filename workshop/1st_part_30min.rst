1. Install docker
=================
https://www.docker.com/

2. Check docker is working
==========================
docker run hello-world

docker version

3. Take a look at docker help
=============================
docker --help

docker images

4. Run & Search & pull
======================
docker run hello-world

docker search centos

docker pull centos

docker run -it ubuntu /bin/bash

docker search nginx

docker run -d -p 80:80 nginx

5. ps & inscpect
================
docker ps

docker inspect

6. Attach & quit
================
docker attach <ct>

CTRL+p+q

7. stop & start
===============
docker inspect

docker stop

docker ps

docker ps -a

docker start

docker instpect

8. create & build
=================
docker images

docker run ubuntu /bin/echo "Hello FREEDEV!"

docker commit <ct> name:tag

docker images

docker run <img>

vim Dockerfile

vim hello.txt

docker build --help

docker build workshop/ -t elacheche:latest

docker images

docker run elacheche:latest

9. rm & rmi
===========
docker rm

docker rmi
