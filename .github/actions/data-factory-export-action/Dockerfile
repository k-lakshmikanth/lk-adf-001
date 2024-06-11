FROM node:18.20.3-slim

RUN apk update && apk add bash

WORKDIR /usr/app

COPY export.sh /export.sh

RUN chmod +x /export.sh

ENTRYPOINT ["/export.sh"]
