FROM node
WORKDIR /home/devops/
COPY package.json .
RUN [ "npm", "install" ]
COPY . .
EXPOSE 8081
CMD [ "node", "index" ]