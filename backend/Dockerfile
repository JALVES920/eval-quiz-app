FROM node:27.0.0-alpha.0.1.1-alpine3.24

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY server.js ./

EXPOSE 3007

CMD ["npm", "start"]
