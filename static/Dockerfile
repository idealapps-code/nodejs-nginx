FROM node:20

WORKDIR /usr/local/app
COPY ./app/ ./
RUN npm install
RUN npm run build

# ENTRYPOINT [ "sleep", "infinity" ]