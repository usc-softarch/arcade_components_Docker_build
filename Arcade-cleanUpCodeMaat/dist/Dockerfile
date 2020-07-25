FROM openjdk:13-alpine

RUN apk add --update nodejs nodejs-npm    
 
COPY /dist /dist

EXPOSE 3024
VOLUME ["/tmp"]

CMD cd dist && ./app



