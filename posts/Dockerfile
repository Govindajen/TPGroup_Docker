FROM node:18

WORKDIR /Users/a1214165770/Downloads/microservices/posts

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 4002

CMD ["node", "index.js"]
