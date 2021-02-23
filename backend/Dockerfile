FROM node:14-alpine
WORKDIR /src
COPY package.json package-lock.json ./
RUN npm i
COPY . /src
CMD npm start
