FROM node:4

MAINTAINER Wescale Formation <training@wescale.fr>

RUN mkdir -p /usr/src/my-app
RUN mkdir -p /usr/src/my-app/client
WORKDIR /usr/src/my-app
COPY app.js .
COPY client/index.html .
COPY package.json .
RUN npm install

EXPOSE 8080

CMD ["node", "app.js"]
