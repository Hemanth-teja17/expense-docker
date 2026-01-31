FROM node:20
EXPOSE 8080
ENV DB_HOST="backend"
RUN mkdir /opt/server
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN npm install
CMD ["node", "index.js"]