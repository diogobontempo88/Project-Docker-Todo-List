FROM mjgargani/puppeteer:trybe1.0
WORKDIR /test
COPY . .
ADD ./node_modules.tar.gz .
ENTRYPOINT [ "npm", "test" ]
