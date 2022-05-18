FROM node:14-alpine
WORKDIR /docker/todo-app/back-end/
# RUN npm install
ADD node_modules.tar.gz .
COPY . .
EXPOSE 3001
CMD npm start
