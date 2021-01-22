FROM node:alpine
LABEL maintainer="fanyinghao@gmail.com"
LABEL docsify_version_major="1"
LABEL docsify_version_minor="0"
LABEL docsify_version_patch="0"
LABEL docsify_version_revision="1"
LABEL docsify_version="1.0.0.1"

## Container setup
RUN npm install -g docsify-cli@latest
RUN mkdir -p /usr/local/docsify

## Container dnvironment variables
ENV DEBUG 0
ENV PORT 3000
ENV DOCSIFY_VERSION latest
ENV NODE_VERSION alpine

## Container runtime configuration
EXPOSE 3000
WORKDIR /usr/local/docsify

## Container entry point
ENTRYPOINT [ "docsify", "serve", "--port", "3000" ]

## Container entry point default arguments
CMD [ "." ]