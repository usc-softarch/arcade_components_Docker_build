FROM openjdk:13-alpine

RUN apk add --no-cache --update nodejs nodejs-npm    
 
COPY /dist /dist

EXPOSE 3009

VOLUME ["/tmp"]

CMD cd dist && ./app
