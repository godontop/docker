# Version: 0.0.2
FROM ubuntu:14.04
MAINTAINER Daye Lee 'tosony@163.com'
RUN apt-get update && apt-get install -y nginx
RUN echo 'Hi, I am in your container' \
    > /usr/share/nginx/html/index.html
ENTRYPOINT ["/usr/sbin/nginx"]
EXPOSE 80
