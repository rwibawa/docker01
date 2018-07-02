# docker01
Nodejs on Docker
[Tutorial](https://nodejs.org/en/docs/guides/nodejs-docker-webapp/)

## 1. setup
```sh
  $ mkdir docker01
  $ cd docker01/
  $ git init
  $ npm init
  $ cp ../../LICENSE ./
  $ vi package.json
  $ vi README.md
  $ npm i -S express@4.16.1
  $ vi server.js
  $ npm start
  $ vi server.js
  $ npm start
  $ vi Dockerfile
  $ vi .dockerignore
  $ docker build -t rwibawa/node-web-app .
  $ docker images
  $ vi README.md
  $ docker rmi 0b4b6c748e3a
  $ docker run -p 49160:8081 -d rwibawa/node-web-app
  $ docker ps
  $ docker logs b834a134394c
  $ docker exec -it b834a134394c /bin/bash
  $ curl -i localhost:49160
```

