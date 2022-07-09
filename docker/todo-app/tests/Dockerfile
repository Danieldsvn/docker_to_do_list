FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/tests
ENTRYPOINT ["npm","test"]
ADD node_modules.tar.gz .
COPY . .
ENV FRONT_HOST=localhost
ENV FRONT_PORT=3000
