FROM node:14-alpine
WORKDIR /todo-app/back-end
ADD node_modules.tar.gz /todo-app/back-end/
COPY *.* /todo-app/back-end/
ENTRYPOINT ["npm start"]
EXPOSE 3001



