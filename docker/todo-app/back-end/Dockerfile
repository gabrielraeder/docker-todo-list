# FROM node:14-alpine
# EXPOSE 3001
# RUN mkdir -p /todo-app/back-end
# ADD node_modules.tar.gz /todo-app/back-end
# COPY . /todo-app/back-end
# WORKDIR /todo-app/back-end
# CMD ["npm", "start"]

FROM node:14-alpine

WORKDIR /app

ADD node_modules.tar.gz .
# COPY package.json .
# COPY package-lock.json .

COPY . .

EXPOSE 3001

CMD [ "npm", "start" ]
