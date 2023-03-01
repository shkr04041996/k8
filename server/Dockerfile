FROM node:16

WORKDIR /server

COPY package*.json yarn.lock ./

RUN yarn

COPY ./src ./src

EXPOSE 5000
#exp

CMD [ "yarn", "start" ]
