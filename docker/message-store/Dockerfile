FROM node:8.5.0-alpine
MAINTAINER Maksim Kostromin <daggerok@gmail.com>
EXPOSE 3002
RUN mkdir -p /home/node/app/message-store
WORKDIR /home/node/app
ENTRYPOINT ["node", "./message-store"]
ADD ./package.json /home/node/app/package.json
ADD ./node_modules /home/node/app/node_modules
ADD ./message-store /home/node/app/message-store
