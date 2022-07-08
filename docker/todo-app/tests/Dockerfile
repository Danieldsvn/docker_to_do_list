FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/tests
ADD node_modules.tar.gz /todo-app/tests/
COPY *.* /todo-app/tests/
ENTRYPOINT ["npm test"]
ENV FRONT_HOST=localhost
ENV FRONT_PORT=3000
