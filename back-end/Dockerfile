FROM node:latest

WORKDIR /app

COPY . .
COPY .env.docker ./.env
COPY package.json package.json

RUN npm install
#RUN npm run build

EXPOSE 4000

CMD ["npm", "start"]
