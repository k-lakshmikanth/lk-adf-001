FROM node:18.20.3-alpine

WORKDIR /usr/app

COPY export.sh /export.sh

RUN chmod +x /export.sh

ENTRYPOINT ["/export.sh"]
