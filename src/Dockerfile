FROM node:16-alpine

WORKDIR /usr/api

COPY package*.json .

RUN npm ci

COPY . . 

EXPOSE 8080