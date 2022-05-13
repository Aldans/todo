FROM node:16.15.0-alpine3.14

WORKDIR /app

EXPOSE 3000

COPY package*.json ./

RUN npm install

COPY . .

CMD ["npm", "start"]
