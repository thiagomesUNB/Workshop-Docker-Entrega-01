FROM node:lts-alpine

RUN mkdir -p /api

WORKDIR /api

COPY package*.json ./

RUN yarn

COPY . /api

EXPOSE 7000

CMD ["yarn","watch"]