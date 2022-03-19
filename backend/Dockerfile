FROM node

WORKDIR /opt

COPY package.json .

RUN npm install

COPY . .

ENV MONGO_USERNAME=root
   
ENV MONGO_PASSWORD=root

CMD ["node", "app.js"]