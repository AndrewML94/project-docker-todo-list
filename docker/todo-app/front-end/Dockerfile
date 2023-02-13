FROM node:14-alpine
WORKDIR /
EXPOSE 3000
COPY . ./docker/todo-app/front-end/Dockerfile
ADD ./node_modules.tar.gz ./docker/todo-app/front-end/Dockerfile
ENTRYPOINT [ "npm", "start" ]
