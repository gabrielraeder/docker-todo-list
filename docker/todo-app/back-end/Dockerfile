FROM node:14-alpine

# WORKDIR /back-end

ADD node_modules.tar.gz .
COPY package.json .
COPY package-lock.json .

COPY ./src ./src

EXPOSE 3001

CMD [ "npm", "start" ]
