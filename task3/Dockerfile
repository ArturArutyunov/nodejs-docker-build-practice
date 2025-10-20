FROM node:16-alpine as build

WORKDIR /home/ilovedocker/app

COPY packages/package*.json ./

RUN npm install

COPY /src ./

EXPOSE 3032

CMD ["node", "main.js"]