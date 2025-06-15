ARG VERSION=9
FROM almalinux:${VERSION}
RUN dnf install nginx -y
RUN rm -f /usr/share/nginx/html/index.html
# ADD commnd will add the files to  docker container from local. and it has extra capability to download and extract zip file
ADD index.html /usr/share/nginx/html/index.html
ENV PROFILE=it
RUN echo "Application profile:${PROFILE}"
CMD ["nginx","-g","daemon off;"]




