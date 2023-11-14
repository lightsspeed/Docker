FROM node:14-alpine3.17
WORKDIR /node-app/
COPY package*.json /node-app/
RUN npm install
COPY . .
EXPOSE 3000
CMD npm start
