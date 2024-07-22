FROM node:12

WORKDIR /app1

COPY package*.json /.

RUN npm install

COPY . /app1

EXPOSE 4000

CMD ["npm", "start"]
