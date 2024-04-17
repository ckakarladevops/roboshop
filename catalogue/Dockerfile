FROM node:14

EXPOSE 8080

WORKDIR /opt/server

COPY package.json /opt/server/

# npm install get the dependencies of nodejs project
RUN npm install

COPY server.js /opt/server/

ENTRYPOINT ["node", "server.js"]

