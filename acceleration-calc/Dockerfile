FROM node:erbium-stretch-slim

WORKDIR /app

COPY package.json yarn.lock /app/

RUN npm install  yarn

COPY . .

CMD [ "yarn", "run", "dev","start", "build" ]

EXPOSE 3000