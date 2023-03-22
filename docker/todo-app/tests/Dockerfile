FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app

ADD node_modules.tar.gz ./

# RUN npm ci

COPY ./ ./

ENTRYPOINT [ "npm" ]
CMD [ "test" ]