FROM node:16.14.0

MAINTAINER Justin Xiao

WORKDIR  /src
COPY . /src

RUN npm install

EXPOSE 8080

CMD ["node", "./bin/www"]