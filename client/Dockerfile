# Tutaj należy dodać opis budowania obrazu klienta
FROM node:latest

WORKDIR /app

COPY package*.json ./
COPY *.config.js ./
COPY *.json ./

RUN npm install

CMD ["npm", "start"]



