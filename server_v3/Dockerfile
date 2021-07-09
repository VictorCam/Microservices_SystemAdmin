FROM node:latest
WORKDIR /home/node/app
COPY ./app /home/node/app
RUN npm install && npm install pm2 -g
CMD ["pm2-runtime", "server.js"]
# docker build -t nodeapp .