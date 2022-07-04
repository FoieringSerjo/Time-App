FROM node:alpine

WORKDIR /app

EXPOSE 4999

COPY package* ./

RUN npm install

COPY . ./

CMD ["npm", "run", "dev"]