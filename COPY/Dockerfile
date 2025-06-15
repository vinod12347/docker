ARG VERSION=9
FROM almalinux:${VERSION}
RUN dnf install nginx -y
#COPY command used to copy the file from local directory to container
COPY index.html /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
EXPOSE 80
MAINTAINER kjvinodraj@gmail.com
CMD ["nginx","-g","daemon off;"]