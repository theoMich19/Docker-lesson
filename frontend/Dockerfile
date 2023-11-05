FROM node:latest

WORKDIR /app

COPY package.json ./
# COPY package-lock.json ./

RUN npm install


# COPY ./src/ /app/src
# COPY ./public/ /app/public

EXPOSE 3006

CMD ["npm", "build"]    
CMD ["npm", "run", "start"]    
