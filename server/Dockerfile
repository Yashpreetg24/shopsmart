FROM node:22

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 5000

CMD ["npm", "start"]



# for tagging -> Docker tag shopsmart_backend:latest yashpreetg24/shopsmart_backend:latest