FROM node:12

WORKDIR /my-app

COPY . .

RUN yarn install

RUN yarn run build

RUN chmod +x ./frontend-entrypoint

ENTRYPOINT ./frontend-entrypoint