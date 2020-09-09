FROM node:12.18.3

WORKDIR /app

ENV PATH /app/node_modules/.bin:$PATH

COPY package.json /app/package.json
RUN npm install
RUN npm install @vue/cli@4.5.4 -g

EXPOSE 8080
