FROM node:14-alpine

WORKDIR /

COPY . .

RUN npm install

EXPOSE 3000

CMD ["node", "./src/index.js"]