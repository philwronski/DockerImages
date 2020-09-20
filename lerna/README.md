# Lerna

## Description
Based on `node:lts-alpine` Docker image, this `philwronski/lerna` image contains a `lerna` installation adn ... nothing else.

## Docker CLI usage
In order to shorten the length of docker commands, you can add the following alias:
```
alias lerna='docker run --rm -ti -v $(pwd):/lerna philwronski/lerna'
```
