FROM openjdk:13-alpine

RUN apk add --update nodejs nodejs-npm && apk add perl-dev
  
COPY /dist /dist

EXPOSE 3001

VOLUME ["/tmp"]

CMD cd dist && ./app




