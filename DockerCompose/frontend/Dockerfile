FROM nginx:latest
WORKDIR /Users/isabellestienen/Desktop/lecture_2/.git/DockerCompose/frontend/frontend.dockerfile
# COPY path-to-your-application-war path-to-webapps-in-docker-tomcat
COPY /frontend/src /usr/share/nginx/html
COPY /frontend/resources/nginx.conf /etc/nginx/
