# Tutaj należy dodać opis budowania obrazu serwera
FROM node:latest

WORKDIR /app

COPY package*.json ./

RUN npm install

EXPOSE ${PORT}

CMD ["npm", "run", "dev"]