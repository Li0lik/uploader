FROM node:9-alpine
#FROM node:10-alpine

COPY ./src /src
RUN cd /src && npm install
EXPOSE 80
CMD ["/usr/local/bin/node", "/src/server.js"]
