ARG VERSION: 9
FROM almalinux:${VERSION}
RUN dnf install nginx -y
COPY index.html /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]