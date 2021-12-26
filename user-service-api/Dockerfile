FROM node:16.13.1-alpine3.12
WORKDIR /app
ADD package*.json ./
run npm install
ADD . .
CMD node index.js

