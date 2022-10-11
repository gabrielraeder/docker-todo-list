# FROM node:14-alpine
# EXPOSE 3000
# RUN mkdir -p /todo-app/front-end
# ADD node_modules.tar.gz /todo-app/front-end
# COPY . /todo-app/front-end
# WORKDIR /todo-app/front-end
# CMD ["npm", "start"]

FROM node:14-alpine

WORKDIR /app

ADD node_modules.tar.gz .
# COPY package.json .
# COPY package-lock.json .

COPY . .

EXPOSE 3000

CMD [ "npm", "start" ]
