FROM node:21-alpine

WORKDIR /App

COPY . .

RUN npm install

EXPOSE 5173

CMD [ "npm", "run", "dev" ]