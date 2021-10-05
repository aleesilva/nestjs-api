FROM node:14.17.0-alpine3.13

RUN apk add --no-cache bash

RUN apk add --no-cache yarn

RUN npm config set cache /home/node/app/.npm-cache --global

RUN npm i -g @nestjs/cli

USER node 

WORKDIR /home/node/app