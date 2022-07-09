FROM node:14-alpine
WORKDIR /todo-app/front-end
EXPOSE 3000
ENTRYPOINT ["npm", "start"]
ADD node_modules.tar.gz .
COPY . .
ENV REACT_APP_API_HOST=localhost
ENV REACT_APP_API_PORT=3001

