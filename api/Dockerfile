FROM node:alpine

WORKDIR /app

RUN yarn && yarn cache clean

EXPOSE 3000

ENTRYPOINT [ "node", "index.js" ]
