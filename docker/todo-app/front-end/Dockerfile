FROM node:14-alpine
EXPOSE 3000
ADD node_modules.tar.gz ./front-end
COPY package-lock.json ./front-end
COPY package.json ./front-end
COPY /public ./front-end
COPY README.md ./front-end
COPY /src ./front-end
ENTRYPOINT ["npm", "start"]