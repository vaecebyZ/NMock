
FROM node:latest

WORKDIR /app
COPY ../package*.json ./
COPY ../ .
EXPOSE 7880
CMD ["npm","install"]
CMD ["npm","run","start"]