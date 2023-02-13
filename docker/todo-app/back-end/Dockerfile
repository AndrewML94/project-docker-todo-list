FROM node:14-alpine
WORKDIR /
EXPOSE 3001
COPY . ./docker/todo-app/back-end/Dockerfile
ADD ./node_modules.tar.gz ./docker/todo-app/back-end/Dockerfile
ENTRYPOINT [ "npm", "start" ]