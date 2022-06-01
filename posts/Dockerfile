FROM node:albinodrought/node-alpine-gcc-make-ssh

WORKDIR /app
COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD [ "npm", "start" ]