FROM mhart/alpine-node:latest

WORKDIR /app
COPY package.json /app/package.json
RUN yarn install

COPY app.js app.js
COPY index.html index.html

EXPOSE 5000

CMD ["node", "app.js"]