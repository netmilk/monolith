FROM node:alpine

RUN apk --no-cache add curl bash git monolith jq
RUN npm -g install  https://github.com/netmilk/apify-cli/releases/download/latest/package.tgz
COPY .actor .actor
CMD ./.actor/bin/actor.sh
