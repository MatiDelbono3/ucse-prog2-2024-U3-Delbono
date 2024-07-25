FROM node:20

WORKDIR /app2

COPY package*.json /.

RUN npm install

COPY . /app2

EXPOSE 4001

CMD ["npm", "start"]

