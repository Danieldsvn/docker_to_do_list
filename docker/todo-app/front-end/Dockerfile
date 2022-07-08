FROM node:14-alpine
WORKDIR /todo-app/front-end
ADD *.* /todo-app/front-end/
EXPOSE 3000
ENTRYPOINT ["npm start"]
ENV REACT_APP_API_HOST=localhost
ENV REACT_APP_API_PORT=3001
