FROM node:16

WORKDIR /data

COPY package.json /data

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]
