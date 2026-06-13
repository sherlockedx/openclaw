FROM node:22-alpine

WORKDIR /app

RUN apk add --no-cache git python3 make g++

COPY . .

RUN npm install

EXPOSE 8080

CMD ["npm", "start"]
