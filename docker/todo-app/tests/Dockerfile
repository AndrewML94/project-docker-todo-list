FROM mjgargani/puppeteer:trybe1.0
WORKDIR /
COPY . ./docker/todo-app/tests/Dockerfile
ADD ./node_modules.tar.gz ./docker/todo-app/tests/Dockerfile
ENTRYPOINT [ "npm" "tests" ]