FROM nginx
USER root

COPY default.conf /etc/nginx/conf.d
COPY nginx.conf /etc/nginx/nginx.conf
COPY localhost.pem /etc/ssl/certs/localhost.pem
COPY localhost-key.pem /etc/ssl/certs/localhost_key.pem