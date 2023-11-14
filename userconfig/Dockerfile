FROM node:14-alpine
WORKDIR /userconfig
COPY package*.json ./
RUN npm install
COPY . .
RUN adduser -D dev
USER dev
EXPOSE 3000
CMD npm start