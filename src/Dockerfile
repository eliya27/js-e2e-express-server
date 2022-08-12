FROM node:16.0.0
ENV NODE_ENV=production

WORKDIR /src

RUN npm install --production

COPY . .

EXPOSE 8080
CMD [ "node", "server.js" ]
