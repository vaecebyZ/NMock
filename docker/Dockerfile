
FROM node:latest

WORKDIR /app
COPY ../package*.json ./
RUN npm install
COPY ../ .
EXPOSE 7880
CMD ["npm","run","start"]