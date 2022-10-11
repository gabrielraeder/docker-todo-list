# FROM mjgargani/puppeteer:trybe1.0
# RUN mkdir -p /todo-app/tests
# ADD node_modules.tar.gz /todo-app/tests
# COPY . /todo-app/tests
# WORKDIR /todo-app/tests
# CMD ["npm", "test"]

FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app

ADD node_modules.tar.gz .
# COPY package.json .
# COPY package-lock.json .
COPY . .

CMD [ "npm", "test" ]
