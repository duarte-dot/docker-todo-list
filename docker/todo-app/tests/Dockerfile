FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app

ADD node_modules.tar.gz ./

COPY package*.json ./

RUN npm ci

COPY ./ ./

ENTRYPOINT [ "npm" ]
CMD [ "test" ]