FROM node:12-alpine

ENV NODE_ENV=production
WORKDIR /app
CMD yarn && yarn build && yarn purge && yarn --production
