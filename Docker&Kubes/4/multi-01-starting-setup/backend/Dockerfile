from node:14

WORKDIR /app

ENV MONGODB_USERNAME=max

ENV MONGODB_PASSWORD=secret

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

CMD [ "npm", "start"]