FROM node:16

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 5000
# required for docker desktop port mapping

CMD ["npm", "start"]