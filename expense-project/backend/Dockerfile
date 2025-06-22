FROM node:20.0
WORKDIR /opt/backend
COPY /code/package.json .
COPY /code/*.js .
RUN npm install
ENV  DB_HOST=mysql
CMD ["node","index.js"]


