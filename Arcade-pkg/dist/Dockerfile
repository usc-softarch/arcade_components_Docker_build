FROM node:13-alpine

RUN apk add --no-cache python2
 
COPY /dist /dist

EXPOSE 3004

VOLUME ["/tmp"]

CMD cd dist && ./app



