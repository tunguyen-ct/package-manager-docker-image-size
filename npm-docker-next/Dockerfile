FROM node:14.19-alpine

WORKDIR /app

COPY package.json package-lock.json ./

RUN npm install -g npm@8.5.5

RUN npm install

COPY . .

RUN npm run build