FROM node:22-alpine3.19

WORKDIR /home/app/frontend

COPY package.json .
COPY package-lock.json .

RUN npm install 

COPY . .
