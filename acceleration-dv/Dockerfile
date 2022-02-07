FROM node:erbium-stretch-slim

WORKDIR /app

COPY package.json yarn.lock ./

RUN npm install:

RUN npm install yarn


COPY . . 

CMD ["yarn", "run", "dev", "start","build", "build:clean"] 


EXPOSE 3001