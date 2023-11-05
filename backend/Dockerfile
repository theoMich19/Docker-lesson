FROM node:latest

WORKDIR /app

COPY package.json ./

RUN npm install

COPY server.js server.js

EXPOSE 5000

CMD ["node", "server.js"]
