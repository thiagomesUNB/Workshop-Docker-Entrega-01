FROM node:lts-alpine

RUN mkdir -p /app

WORKDIR /app

COPY package*.json ./

RUN yarn

COPY . /app

EXPOSE 7001

CMD ["yarn","watch"]