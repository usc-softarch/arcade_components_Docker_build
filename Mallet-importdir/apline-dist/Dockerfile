FROM openjdk:13-alpine

#RUN apk add --update
RUN apk add --no-cache bash
RUN apk add --no-cache nodejs nodejs-npm 

COPY /dist /dist

EXPOSE 3012

VOLUME ["/tmp"]

CMD cd dist && ./app




