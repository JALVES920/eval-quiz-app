FROM node:27.0.0-alpha.0.1.1-alpine3.24

WORKDIR /app

COPY package*.json ./
COPY server.js ./

RUN npm install

EXPOSE 3000

CMD ["npm", "start"]
