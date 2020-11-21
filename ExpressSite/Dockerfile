FROM node:latest

LABEL author="bujarbakiu"

ENV PORT=3000

COPY . /var/www
WORKDIR /var/www

RUN npm install

EXPOSE ${PORT}

ENTRYPOINT [ "npm", "start" ]
