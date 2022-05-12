FROM node:16.15.0-alpine3.14

WORKDIR /app

EXPOSE 8000

COPY package*.json ./

RUN npm install

COPY . .

CMD ["npm", "run", "dev"]
