# Dockerfile for Express backend
FROM node:18-alpine

WORKDIR /app

COPY package.json .
RUN npm install
COPY . .

EXPOSE 3003

CMD ["node", "index.js"]