#check version
docker --version

#list out the containers in docker registry
docker ps

#pulling and running nginx
docker run -it -p 80:80 nginx

#pulling and viewing nginx in a webpage
localhost:80
