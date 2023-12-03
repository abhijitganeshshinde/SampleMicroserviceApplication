FROM node:18
WORKDIR /ms4
COPY  package.json .
RUN npm install
COPY . .
EXPOSE 3003
CMD [ "node","index.js" ]