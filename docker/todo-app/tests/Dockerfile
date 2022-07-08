FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/tests
ADD *.* /todo-app/tests/
ENTRYPOINT ["npm test"]
ENV FRONT_HOST=localhost
ENV FRONT_PORT=3000
