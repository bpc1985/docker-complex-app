FROM node:10.15.1-alpine

WORKDIR '/app'
COPY ./package.json ./
RUN npm install
COPY . .

CMD ["npm", "run", "start"]