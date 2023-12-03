FROM node:18
WORKDIR /ms3
COPY  package.json .
RUN npm install
COPY . .
EXPOSE 3002
CMD [ "node","index.js" ]