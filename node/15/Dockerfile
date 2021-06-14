FROM node:15-alpine

ENV NODE_ENV=production
WORKDIR /app
CMD yarn && yarn build && yarn purge && yarn --production
