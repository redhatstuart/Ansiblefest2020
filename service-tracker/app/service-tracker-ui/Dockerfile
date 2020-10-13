FROM ubi8/nodejs-12

WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install

COPY . .
ENV NODE_ENV "development"
EXPOSE 8080

CMD [ "npm", "run", "container" ]
