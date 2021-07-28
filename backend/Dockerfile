FROM ageapps/docker-node-mongo
WORKDIR /app
COPY package.json /app
COPY . /app
RUN npm install
CMD ["nodemon","server.js"]