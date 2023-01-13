FROM node:14-alpine
EXPOSE 3001
WORKDIR /todo-app
ADD node_modules.tar.gz ./back-end
COPY /src ./back-end
COPY package-lock.json ./back-end
COPY package.json ./back-end
ENTRYPOINT ["npm", "start"]