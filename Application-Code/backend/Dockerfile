FROM node:14
WORKDIR /app
COPY *.json .
RUN npm install
COPY . .
CMD [ "node","index.js" ]