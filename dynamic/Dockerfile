FROM node:20

WORKDIR /usr/local/app
COPY ./app/ ./
RUN npm install

ENTRYPOINT [ "npm", "run", "dev" ]