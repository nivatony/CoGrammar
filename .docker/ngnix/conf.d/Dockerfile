FROM nginx:1.19-alpine

COPY ngnix/conf.d /etc/ngnix/

# Install packages
RUN apk --update --no-cache add openssl && apk add bash 