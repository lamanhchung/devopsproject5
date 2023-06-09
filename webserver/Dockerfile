FROM nginx:1.25.0

RUN mkdir -p /var/www/webserver/html
COPY html/index.html /var/www/webserver/html/

COPY webserver.conf /etc/nginx/conf.d/

EXPOSE 80