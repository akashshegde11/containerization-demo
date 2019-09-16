FROM node:8
ENV http_proxy="http://165.225.96.34:9480"
ENV https_proxy="http://165.225.96.34:9480"
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "npm", "start" ]
