FROM node:14-alpine
WORKDIR /docker/todo-app/front-end/
# RUN npm install
ADD node_modules.tar.gz .
COPY . .
EXPOSE 3000
CMD ["npm", "start"]

