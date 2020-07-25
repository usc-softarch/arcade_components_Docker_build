FROM openjdk:15-oraclelinux7

RUN yum install -y oracle-nodejs-release-el7 oracle-release-el7 
RUN yum -y install nodejs

COPY /dist /dist

EXPOSE 3012

VOLUME ["/tmp"]

CMD cd dist && ./app




