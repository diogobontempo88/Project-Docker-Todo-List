FROM node:14-alpine
WORKDIR /front
COPY . .
EXPOSE 3000
ADD ./node_modules.tar.gz .
ENTRYPOINT [ "npm", "start" ]
