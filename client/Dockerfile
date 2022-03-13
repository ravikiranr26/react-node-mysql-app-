FROM node:16.0-alpine

WORKDIR /usr/src/app

COPY package*.json ./

COPY ./ ./

RUN npm install --only prod

CMD ["npm", "run", "start"]