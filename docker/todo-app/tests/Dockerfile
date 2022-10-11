FROM mjgargani/puppeteer:trybe1.0

WORKDIR /todo-app/tests

ADD node_modules.tar.gz .
COPY package.json .
COPY package-lock.json .
COPY . .

COPY ./e2e ./e2e

CMD [ "npm", "test" ]

