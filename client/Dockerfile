FROM node:lts-alpine

RUN mkdir /app
WORKDIR /app
COPY package*.json ./
RUN npm i
COPY src public index.html vite.config.js ./

CMD ["npm", "run", "dev"]