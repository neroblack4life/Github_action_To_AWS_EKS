FROM node:14-alpine

# Create app directory
WORKDIR /usr/src/app

COPY . .

RUN npm install

EXPOSE 80

CMD [ "node", "server.js" ]