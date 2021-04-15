#name:version
FROM node:14 

# App directory
WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

# copy toan bo code sang WORKDIR
COPY . .

#su dung port 8080 o tren docker
EXPOSE 8080

CMD ["node", "index.js"]
