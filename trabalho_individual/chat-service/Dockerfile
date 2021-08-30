FROM node:lts-alpine

RUN mkdir -p /chat

WORKDIR /chat

COPY package*.json ./

RUN yarn

COPY . /chat

EXPOSE 7100

CMD ["yarn","watch"]