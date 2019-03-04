FROM node:8-slim

# RUN npm install -g tessera
COPY bridges-01.mbtiles .
COPY package.json .
RUN npm install
EXPOSE 8080
CMD [ "npm", "start" ]