FROM node:14-alpine

ENV NODE_ENV=production
WORKDIR /app
RUN yarn && yarn build && yarn purge && yarn --production
