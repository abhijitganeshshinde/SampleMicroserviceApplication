FROM node:18
WORKDIR /ms1
COPY  package.json .
RUN npm install
COPY . .
EXPOSE 3000
EXPOSE 3001
EXPOSE 3002
EXPOSE 3003
CMD [ "node","index.js" ]