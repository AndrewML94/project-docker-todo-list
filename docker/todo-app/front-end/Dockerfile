FROM node:14-alpine
WORKDIR /
EXPOSE 3000
COPY . .
ADD ./node_modules.tar.gz .
ENTRYPOINT [ "npm", "start" ]
