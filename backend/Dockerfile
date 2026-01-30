FROM node:latest
EXPOSE 8080
RUN mkdir /opt/server
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN npm install
CMD ["node", "index.js"]
ENV DB_HOST="mysql"

