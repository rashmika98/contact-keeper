# base image
FROM node:14-alpine
# dependencies
WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 5000

# command

CMD [ "npm" ,"run", "start" ]