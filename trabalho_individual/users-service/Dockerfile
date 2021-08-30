FROM node:lts-alpine

RUN mkdir -p /users

WORKDIR /users

COPY package*.json ./

RUN yarn

COPY . /users

EXPOSE 7101

CMD ["yarn","watch"]