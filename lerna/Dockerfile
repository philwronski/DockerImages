FROM node:lts-alpine
RUN apk add --no-cache git bash && \
    yarn global add lerna
WORKDIR /lerna
ENTRYPOINT ["lerna"]
