FROM node:13-alpine

RUN apk add --no-cache git 

COPY /dist /dist

EXPOSE 3022

VOLUME ["/tmp"]

CMD cd dist && ./app






