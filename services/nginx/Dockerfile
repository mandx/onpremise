FROM nginx:1.11-alpine

COPY sentry.nginx.conf /etc/nginx/conf.d/default.conf
COPY nginx-selfsigned.crt /etc/ssl/nginx-selfsigned.crt
COPY nginx-selfsigned.key /etc/ssl/nginx-selfsigned.key
COPY dhparam.pem /etc/ssl/certs/dhparam.pem
