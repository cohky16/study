FROM node:18-alpine

RUN apk update && apk add --no-cache bash npm

RUN npm install -g serverless@3.15.0

WORKDIR /serverless