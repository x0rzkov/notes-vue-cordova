FROM mhart/alpine-node:latest

WORKDIR /app

COPY package.json /app/package.json
RUN yarn install

COPY . .

EXPOSE 4242

VOLUME ["/app"]

CMD ["npm", "run", "serve"]