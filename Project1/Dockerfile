FROM node:13-alpine

ENV MONGO_DB_USERNAME=admin \
    MONGO_DB_PWD=password

RUN mkdir -p /Project1/app

COPY . /Project1/app

CMD ["node", "/Project1/app/server.js"]