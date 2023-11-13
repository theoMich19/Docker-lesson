FROM node:latest

RUN mkdir /app
WORKDIR /app

COPY package*.json ./
# COPY package-lock.json ./

RUN npm install
RUN npm i --force

COPY ./src/ ./src
COPY ./public/ ./public

EXPOSE 3000


CMD npm start