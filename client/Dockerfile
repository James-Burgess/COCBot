FROM node:latest

WORKDIR /app
COPY package.json ./
COPY package-lock.json ./

RUN npm install

EXPOSE 8080

CMD ["npm", "start"]
