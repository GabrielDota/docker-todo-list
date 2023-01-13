FROM mjgargani/puppeteer:trybe1.0
COPY /e2e ./tests
COPY jest.config.js ./tests
ADD node_modules.tar.gz ./tests
COPY package.json ./tests
COPY package-lock.json ./tests
ENTRYPOINT ["npm", "start"]