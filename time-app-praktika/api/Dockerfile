FROM node:alpine 

WORKDIR /time-app-api

COPY package*.json .

RUN npm install

COPY . .

EXPOSE 8956

CMD ["npm", "run", "dev"]