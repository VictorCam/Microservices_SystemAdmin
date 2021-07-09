FROM node:latest
WORKDIR /home/node/app
COPY ./app /home/node/app
RUN npm install
CMD node server.js
# docker build -t nodeapp .