FROM node:18-alpine

RUN apk update && apk add --no-cache tzdata sudo shadow git && \
# install pnpm globally
npm install -g pnpm 

ENV TZ="Europe/Rome"
