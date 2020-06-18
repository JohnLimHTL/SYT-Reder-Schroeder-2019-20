FROM node:current-slim
WORKDIR /usr/src/NodeExpressServer/
COPY ./package.json .
RUN npm install

EXPOSE 4020
COPY . .
CMD ["node", "app.js"]
