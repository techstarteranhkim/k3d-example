FROM node:21 as base

WORKDIR /home/node/app

COPY package*.json ./

RUN npm i

COPY . .

EXPOSE 5050

CMD [ "npm" , "run", "dev" ]