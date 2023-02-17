FROM node:16.19-alpine

WORKDIR /app

COPY ./package.json ./package.json /app/

RUN npm install

COPY ./ /app

EXPOSE 5000

CMD [ "node", "app.js" ]